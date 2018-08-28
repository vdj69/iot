# iot
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![StackShare](https://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](https://stackshare.io/mmontes11/iot)

Generic purpose Internet of Things platform. It consists of the following parts:

* [iot-server](https://github.com/mmontes11/iot-server)
* [iot-worker](https://github.com/mmontes11/iot-worker)
* [biot](https://github.com/mmontes11/biot)
* [iot-client](https://github.com/mmontes11/iot-client)
* [iot-raspi-sensors](https://github.com/mmontes11/iot-raspi-sensors)
* [iot-raspi-door](https://github.com/mmontes11/iot-raspi-door)
* [iot-web](https://github.com/mmontes11/iot-web)

### Configuration

* [.env](https://github.com/mmontes11/iot/blob/develop/.env)
* [nginx](https://github.com/mmontes11/iot/blob/develop/nginx)
* [mosquitto](https://github.com/mmontes11/iot/blob/develop/mosquitto)
* [iot-server/.env](https://github.com/mmontes11/iot-server/blob/develop/.env)
* [iot-worker/.env](https://github.com/mmontes11/iot-worker/blob/develop/.env)
* [biot/.env](https://github.com/mmontes11/biot/blob/develop/.env)
* [iot-web/.env](https://github.com/mmontes11/biot/blob/develop/.env)


### Development

```bash
$ ./run-development.sh 
```

### Production

```bash
$ ./run-production.sh 
```

### Things

Once backend is up and running, you can start deploying things:

* [iot-raspi-sensors](https://github.com/mmontes11/iot-raspi-sensors)
* [iot-raspi-door](https://github.com/mmontes11/iot-raspi-door)
