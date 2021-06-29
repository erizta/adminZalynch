<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/erizta/adminZalynch">
    <img src="logo.png" alt="Logo" width="300" height="80">
  </a>

  <h3 align="center">Zalynch Administrator</h3>

  <p align="center">
    An awesome Admin Web App!
    <br />
    <a href="https://github.com/erizta/adminZalynch"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/erizta/adminZalynch">View Demo</a>
    ·
    <a href="https://github.com/erizta/adminZalynch/issues">Report Bug</a>
    ·
    <a href="https://github.com/erizta/adminZalynch/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

![Zalynch Admin][product-screenshot]

AdminZalynch is a web application for administrator to manage the contents, such as create, update, and delete data of the products.

### Built With

-   [Tailwind](https://tailwindcss.com)
-   [JQuery](https://jquery.com)
-   [Laravel](https://laravel.com)
-   [Jetstream](https://jetstream.laravel.com)
-   [Laracast](https://laracasts.com)

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

-   npm
    ```sh
    npm install npm@latest -g
    ```

### Installation

1. Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs/5.4/installation#installation)

2. Alternative installation is possible without local dependencies relying on [Docker](#docker).
3. Clone the repository
    ```sh
    git clone https://github.com/erizta/adminZalynch.git
    ```
4. Switch to the repo folder
    ```sh
    cd adminZalynch
    ```
5. Install all the dependencies using composer
    ```php
    composer install
    ```
6. Copy the example env file and make the required configuration changes in the .env file
    ```sh
    cp .env.example .env
    ```
7. Generate a new application key
    ```php
    php artisan key:generate
    ```
8. Run the database migrations (Set the database connection in .env before migrating)
    ```php
    php artisan migrate
    ```
9. Start the local development server
    ```php
    php artisan serve
    ```
**TL;DR command list**

    git clone git@github.com:erizta/adminZalynch.git
    cd adminZalynch
    composer install
    cp .env.example .env
    php artisan key:generate
You can now access the server at http://localhost:3000

**Make sure you set the correct database connection information before running the migrations** [Environment variables](#environment-variables)

    php artisan migrate
    php artisan serve

<!-- USAGE EXAMPLES -->

## Usage

## Database seeding

**Populate the database with seed data with relationships which includes users, articles, comments, tags, favorites and follows. This can help you to quickly start testing the api or couple a frontend and start using it with ready content.**

Open the DummyDataSeeder and set the property values as per your requirement

    database/seeds/DummyDataSeeder.php

Run the database seeder and you're done

    php artisan db:seed

***Note*** : It's recommended to have a clean database before seeding. You can refresh your migrations at any point to clean the database by running the following command

    php artisan migrate:refresh

_For more examples, please refer to the [Documentation](https://example.com)_

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/erizta/Best-README-Template/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

Erizta Alifa P - [erizta](https://linkedin.com/in/erizta) - eriztaalifad@gmail.com

Project Link: [https://github.com/erizta/adminZalynch](https://github.com/erizta/adminZalynch)

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

-   [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
-   [Img Shields](https://shields.io)
-   [Choose an Open Source License](https://choosealicense.com)
-   [GitHub Pages](https://pages.github.com)
-   [Animate.css](https://daneden.github.io/animate.css)
-   [Loaders.css](https://connoratherton.com/loaders)
-   [Slick Carousel](https://kenwheeler.github.io/slick)
-   [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
-   [Sticky Kit](http://leafo.net/sticky-kit)
-   [JVectorMap](http://jvectormap.com)
-   [Font Awesome](https://fontawesome.com)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[product-screenshot]: 11.png
