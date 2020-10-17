<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">BOOKSTORE WEB APP</h3>

  <p align="center">
    View, review, and buy books!
    <br />
    <br />
    <a href="https://agile-badlands-93852.herokuapp.com/">View Website</a>
    ·
    ·
    <br/>
    <a href="https://github.com/Toluwalemi/django-bookstore-app/issues">Report Bug</a>
    ·
    <a href="https://github.com/Toluwalemi/django-bookstore-app/issues">Request Feature</a>
  </p>
</p>

## 🚀 Features
 - Orders with Stripe


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Built With](#built-with)
* [Getting Started](#getting-started)  
  * [Installation](#installation)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)


<!-- ABOUT THE PROJECT -->

### Built With

* [Django](https://www.djangoproject.com/)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Installation
 
```sh
$ https://github.com/Toluwalemi/django-bookstore-app.git
$ cd django-bookstore-app
```

## Docker
```sh
$ docker build .
$ docker-compose up -d
$ docker-compose exec web python manage.py migrate
$ docker-compose exec web python manage.py createsuperuser
$ docker-compose exec web python manage.py runserver
# Load the site at http://127.0.0.1:8000
```
## Pipenv
```sh
$ pipenv install
$ pipenv shell
(django-bookstore-app) $ python manage.py migrate
(django-bookstore-app) $ python manage.py createsuperuser
(django-bookstore-app) $ python manage.py runserver
# Load the site at http://127.0.0.1:8000
```


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/Toluwalemi/django-bookstore-app/issues) for a list of proposed features (and known issues).

<!-- 🤝 CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

[The MIT License](LICENSE)

Distributed under the MIT License. See `LICENSE` for more information.
