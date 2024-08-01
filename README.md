# Node.js URL Shortener with Visit Tracker and Authentication

This repository contains a URL shortener service built with Node.js and EJS. It allows authenticated users to enter long URLs which are then shortened using a randomly generated `shortid`. The service keeps track of how many times each shortened URL is visited, providing insights into the popularity of the linked sites.

## Features

- **URL Shortening:** Converts long URLs into manageable short links with unique identifiers.
- **Visit Tracking:** Monitors and records the number of visits to each shortened URL.
- **MongoDB Integration:** Utilizes MongoDB to store and manage URL mappings, visit counts, and user data.
- **User Authentication:** Includes login and signup functionality to manage user accounts.
- **User-specific URL Management:** Logged-in users can view and manage their generated short links.
- **Public Access to Short Links:** Generated links can be accessed and used by anyone, even without authentication.

## Technologies Used

- **Node.js:** For server-side logic and handling HTTP requests.
- **EJS:** As a templating engine to render dynamic HTML pages.
- **MongoDB:** As a NoSQL database to store URL, tracking, and user data.
- **Express.js:** Web application framework for Node.js.

## Screenshots

![Home Screen](screenshots/home_screen.png)
*Home screen showing generated links and their click counts*

![Login Page](screenshots/login_page.png)
*Login page for user authentication*

![Signup Page](screenshots/signup_page.png)
*Signup page for new user registration*
