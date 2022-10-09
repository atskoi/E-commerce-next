<br />
<p align="center">
  <a href="https://github.com/anilsenay/next-e-commerce">
    <img src="https://i.ibb.co/ZzG3GtN/index.png" alt="Header photo" >
  </a>
  <h3 align="center">E-Commerce Website</h3>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [About the Project](#about-the-project)
  - [Built With](#built-with)
- [Screenshots](#screenshots)
  - [Home (News In)](#news-in)
  - [Categories](#categories)
  - [Product](#product)
  - [Cart](#cart)
  - [Account](#account)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Issues / Feature Plans](#issues---future-plans)
- [Contributing](#contributing)
- [Questions & Answers](#q--a)
- [License](#license)
- [Contact](#contact)

<!-- ABOUT THE PROJECT -->

## About The Project

- Filter and Sort buttons are not working yet.
- ~~Website is not responsive %100 because of time was not enought. I am working on it currently.~~ Now, it is responsive.
- Firebase functions could be better
- Home page(News In) cards has no redirects. They are just placeholders.

### Built With

- [React](https://reactjs.org)
- [NextJS](https://nextjs.org/)
- [Firebase](https://firebase.google.com/docs/web/setup)
- [React Hook Form](https://react-hook-form.com/)
- [date-fns](date-fns.org/)
- [Sass](https://sass-lang.com/)

<!-- Screens -->

## Screenshots

### News In

![Home Image](https://i.ibb.co/ZzG3GtN/index.png)
- Cards has no links and they are static, they are just placeholders.

### Categories

![Categories Image](https://i.ibb.co/ScCBXDZ/index2.png)

### Product

![Product Image](https://i.ibb.co/mbsd2Y1/index5.png)

### Cart

![Cart Image](https://i.ibb.co/svHtw0H/index3.png)

### Account

![Account Image](https://i.ibb.co/JcR3x7F/index4.png)

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) version 10.13 or later
- [Git](https://git-scm.com/) (I used 2.20.1)

### Installation

1. You need to create a firebase project

2. Clone the repo and change the directory

```sh
git clone https://github.com/anilsenay/next-e-commerce.git
cd next-e-commerce
```

3. Install NPM packages

```sh
npm install
```

4. Create your .env.local file on root folder(next-e-commerce) with this content. Put your firebase keys.

```
NEXT_PUBLIC_FIREBASE_API_KEY = your-firebase-api-key
NEXT_PUBLIC_FIREBASE_PROJECT_ID = your-firebase-project-id
NEXT_PUBLIC_FIREBASE_APP_ID = your-firebase-app-id
```

5. Run in development mode

```sh
npm run dev
```

