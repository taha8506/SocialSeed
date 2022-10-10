<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
 
  <h3 align="center">Social Seed</h3>

  <p align="center">
    The social media network for plant fanatics!
    <br />
    <a href="https://github.com/taha8506/SocialSeed"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://social-seed-app.herokuapp.com/">View Demo</a>
   
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
   
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Social Seed Screenshot][product-screenshot]](https://i.ibb.co/f0vXw6K/socialseed.png)

Social Seed is a fullstack app that allows the user CRUD functionality and my first full stack application. This is a passion project for me to really flex my skills in fullstack development. This apps allows the user to create posts with images, commenting, liking, deleting, user authentication, and more.

### Built With

Bootstrap, Tailwind, Express, MongoDB, Node, Passport. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### NPM ADDONS USED

* "bcrypt"
*  "cloudinary"
*   "connect-mongo"
*   "dotenv"
*   "ejs"
*   "express"
*   "express-flash"
*   "express-session"
*   "method-override"
*   "mongodb",
*   "mongoose"
*   "morgan"
*   "multer"
*   "nodemon"
*   "passport"
*   "passport-local"
*   "validator"


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/taha8506/socialseed.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your DB String, Cloudinary, Cloud name, Api key, Api secret in `.env`
   ```js
   const DB_STRING = 'ENTER YOUR KEY';
   const CLOUD_NAME = 'ENTER YOUR KEY';
   const API_KEY = 'ENTER YOUR KEY';
   const API_SECRET = 'ENTER YOUR KEY';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


[product-screenshot]: public/imgs/screenshot.PNG
