# Simple docker-compose based Prometheus / Grafana config

## Prerequisites

Have [Docker](https://www.docker.com/products/docker-desktop/) installed and running

## Usage

Values for image versions and other configuration (like username / passwords) are in the  `.env` file.

```sh 
docker copmose up -d

open http://localhost:3000
```


## Additional Resources
* https://github.com/vegasbrianc/prometheus
