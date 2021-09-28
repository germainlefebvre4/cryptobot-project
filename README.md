# Cryptobot

This project aims to manage bots generated by [https://github.com/whittlem/pycryptobot](https://github.com/whittlem/pycryptobot).

The project is composed with the following repositories:
* [cryptobot-project](https://github.com/germainlefebvre4/cryptobot-project): (this repo) The board project where to submit `ISSUES` and discuss about it.
* [cryptobot-meta](https://github.com/germainlefebvre4/cryptobot-meta): The meta project where to begin and clone the whole project repositories. Start from HERE!
  * [cryptobot-front](https://github.com/germainlefebvre4/cryptobot-front): The front-side source code written in NodeJS 12 with the [VueJS](https://github.com/vuejs/vue) framework.
  * [cryptobot-api](https://github.com/germainlefebvre4/cryptobot-api): The API-side source code written in Python 3 with the [FastAPI](https://github.com/tiangolo/fastapi) framework.
  * [cryptobot-controller](https://github.com/germainlefebvre4/cryptobot-controller): The API-backed in-cluster (kubernetes cluster) inspector source code written in Python 3 with the [FastAPI](https://github.com/tiangolo/fastapi) framework.
  * [cryptobot-operator](https://github.com/germainlefebvre4/cryptobot-operator): The Kubernetes operator that manage cryptobots inside the kubernetes cluster written in Python 3 withe the framework [Kopf](https://github.com/nolar/kopf).
