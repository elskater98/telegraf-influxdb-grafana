# telegraf-influxdb-grafana
## Set up
    docker-compose up -d
    
The environment variables are located in the `influxdb2.env` and `grafana.env` files. It is highly recommended to change the password and token in a production environment. Also, remind that the first time we log in Grafana, the user is `admin` and the password is `admin`; after that, you are free to change it.
