# Akll-docker-compose

## Installation
- Clone this repository
- `cd akll-main`
- Clone [akll-frontend](https://github.com/kalaztaja/akll-frontend) and [AKL-2020-Backend](https://github.com/Akzuu/AKL-2020-Backend)
- Generate certificates with `sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout localhost.key -out localhost.crt -config localhost.conf`
- Fill in .env for backend env variables in `AKL-2020-Backend/.env`
- Fill in .env.akl and .env.all frontend env variables in `akll-frontend`
- `sudo docker-compose build`
- `sudo docker-compose up`
