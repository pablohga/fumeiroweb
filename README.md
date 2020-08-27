Fumeuro na Brasa Delivery - Painel Administrativo

Este sistema é composto por API, App Mobile, Painel Administrativo e Painel de Atendimento. Todo inclusos neste GitHub. Duvidas e esclarecimentos, entre em contato por pablohga@gmail.com . Caso deseje este sistema para o seu restuarante e se livrar do UBER EATS de vez, estarei disponivel para desenvolver uma versão persoanlizada para você!

## Try it now

I deployed this project on Netlify, try it out: [pizza-delivery.com](https://pizza-delivery.netlify.com)

- email: `admin@delivery.com`
- password: `123456`

**Note**
Remember that this web app is for managing the application, try the [app for customers](https://github.com/CaioQuirinoMedeiros/delivery_app) too

## :arrow_down: Installing

**Cloning the repo**

```shell
git clone https://github.com/CaioQuirinoMedeiros/delivery_web.git

cd delivery_web
```

**Installing dependencies**

```shell
yarn install
```

## :satellite: Connecting with the server API

1. Follow the instructions on [delivery-api](https://github.com/CaioQuirinoMedeiros/delivery_api) to have the server up and running
2. Create a _.env_ file and set a variable `REACT_APP_API_URL` with the value of your server url

- It should looks like this: `CREATE_APP_API_URL=http://127.0.0.1:3333`

## :runner: Running
run in development mode
```shell
yarn start
```
or you can build and then serve the build folder
```shell
yarn build
```
