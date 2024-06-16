# Personal Card

This is a simple personal card webpage that showcases basic information, social media links, and interactive buttons using HTML and CSS.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Contact](#contact)

## Overview

The personal card project is designed to provide a compact, stylish representation of an individual's profile. It includes a profile picture, name, job title, social media links, and interactive buttons for subscribing and messaging. The card also displays social engagement metrics like likes and comments.

## Features

- Profile picture and personal information display
- Social media links with icons
- Interactive buttons for subscription and messaging
- Display of likes, thumbs up, and comments
- Hover effects for buttons

## Technologies Used

- HTML5
- CSS3
- Boxicons

## Setup

To set up this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd your-repository
    ```

3. **Open the project in your preferred code editor**.

## Usage

To view the personal card locally, you can simply open the `index.html` file in your web browser.

1. **Open `index.html`**:
    - Double-click the `index.html` file, or
    - Right-click the `index.html` file and select "Open with" and choose your web browser

## HTML Structure

The HTML file consists of the following sections:
- **Header**: Includes meta tags and links to external stylesheets.
- **Body**: Contains the personal card container with profile information, social media links, and interactive buttons.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Card</title>
    <link rel="stylesheet" href="PerCard.css">
    <link href='https://unpkg.com/boxicons@2.1.2/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <div class="container">
        <div class="image">
            <img src="person.jpg" alt="profilepic">
        </div>
        <div class="intro">
            <span class="name">Muhammad Uzair</span>
            <span class="Job">Web Developer</span>
        </div>
        <div class="media">
            <a href="#" class="logo" style="background-color: blue;">
                <i class='bx bxl-facebook'></i>
            </a>
            <a href="#" class="logo" style="background: #e1306c;">
                <i class='bx bxl-instagram'></i>
            </a>
            <a href="#" class="logo" style="background-color: red;">
                <i class='bx bxl-youtube'></i>
            </a>
            <a href="#" class="logo" style="background-color: skyblue;">
                <i class='bx bxl-twitter'></i>
            </a>
        </div>
        <div class="button">
            <button type="button" class="But">Subscribe</button>
            <button type="button" class="But">Message</button>
        </div>
        <div class="like">
            <i class='bx bx-heart'></i>
            <span class="num">60k | </span>
            <i class='bx bx-like'></i>
            <span class="num">60k | </span>
            <i class='bx bx-message-rounded-dots'></i>
            <span class="num">60</span>  
        </div>
    </div>
</body>
</html>
