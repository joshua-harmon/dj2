# vue-django

<!-- ABOUT THE PROJECT -->

## About The Project

It's a pretty basic todo list with the only intent of studying new technologies and self-improvement.

### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

- Docker
- Vue
- Django
- CircleCI
- Heroku

### How to run

Install Docker to your machine and run:

```sh
docker compose up
```

or

Install Node and Python, open two different terminal tabs and run these two commands:

```sh
./manage.py runserver
```

```sh
cd frontend && yarn serve
```

### Deploy

To deploy the application all you need to do is run `yarn build` in the frontend folder and push the changes to this repo. CircleCI will automatically start the build/deploy process to Heroku, which will be displayed in this URL:
https://utzigui-vue-django.herokuapp.com/

### TODO

- Automate to automatically build before push
- Fix docker compose
