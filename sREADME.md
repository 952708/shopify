<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/sathish/reactjs-food-order-app">
    <img src="images/letter-P-circle.svg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Food Order App</h3>

  <p align="center">
  Order Delicious Food using this application. Easy to use and fast to order...
  This application is built using React JS for frontend and Firebase for database.
    <br />
    <a href="https://github.com/sathish/reactjs-food-order-app"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/sathish/reactjs-food-order-app">View Demo</a>
    ·
    <a href="https://github.com/sathish/reactjs-food-order-app/issues">Report Bug</a>
    ·
    <a href="https://github.com/sathish/reactjs-food-order-app/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
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
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## OUTPUT IMAGES

<img src="images/screenshot-1.png"  />
<img src="images/screenshot-2.png"  />

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

- [![React][react.js]][react-url]
- [Firebase](https://firebase.google.com)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

### Prerequistes

- Create a firebase account or use your existing account to log in.
- Feel free to use your own data and database provider. But the json content over the request must be in the **below format**.
- Create a database name and add content in it.
  > Id of the item -> then fields _description_ _name_ _price_ with same names refer [AvailableMeals.jsx](src/components/Meals/AvailableMeals.jsx) **line 6**

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/sathish/reactjs-food-order-app.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Change the url to your database url in the [AvailableMeals.jsx](src/components/Meals/AvailableMeals.jsx) and [Cart.jsx](src/components/Cart/Cart.jsx).

   > Make sure you add the "database.json" to the url end!

4. Run the following code.
   ```sh
   npm start
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/sathish/reactjs-food-order-app.svg?style=for-the-badge
[contributors-url]: https://github.com/sathish/reactjs-food-order-app/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/sathish/reactjs-food-order-app.svg?style=for-the-badge
[forks-url]: https://github.com/sathish/reactjs-food-order-app/network/members
[stars-shield]: https://img.shields.io/github/stars/sathish/reactjs-food-order-app.svg?style=for-the-badge
[stars-url]: https://github.com/sathish/reactjs-food-order-app/stargazers
[issues-shield]: https://img.shields.io/github/issues/sathish/reactjs-food-order-app.svg?style=for-the-badge
[issues-url]: https://github.com/sathish/reactjs-food-order-app/issues
[license-shield]: https://img.shields.io/github/license/sathish/reactjs-food-order-app.svg?style=for-the-badge
[license-url]: https://github.com/sathish/reactjs-food-order-app/blob/master/LICENSE.txt
[product-screenshot]: images/screenshot.png
[next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[next-url]: https://nextjs.org/
[react.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[react-url]: https://reactjs.org/
[vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[vue-url]: https://vuejs.org/
[angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[angular-url]: https://angular.io/
[svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[svelte-url]: https://svelte.dev/
[laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[laravel-url]: https://laravel.com
[bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[bootstrap-url]: https://getbootstrap.com
[jquery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[jquery-url]: https://jquery.com
