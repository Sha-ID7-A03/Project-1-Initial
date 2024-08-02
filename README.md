# Tools of Gold - Homepage

This repository contains the HTML code for the homepage of "Tools of Gold," a website showcasing one of the largest manufacturers of tools, ranging from plumbing to mining.

## Description

The homepage includes a navigation bar, a title section, and a brief description of the company's offerings. The design uses Google Fonts for enhanced typography and includes a link to an external CSS file for styling.

## Features

- Responsive design with a viewport meta tag
- Custom fonts from Google Fonts
- Navigation bar with links to various sections of the website
- Introductory text and a call-to-action button

## Code Structure

```plaintext
index.html
homrpage.css
```

### index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tools - Home</title>
  <link rel="stylesheet" href="homrpage.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Edu+AU+VIC+WA+NT+Hand:wght@600&family=Playwrite+BE+VLG:wght@100&family=Rajdhani:wght@500&display=swap" rel="stylesheet">
</head>
<body>
  <!-- Navbar -->
  <div class="Top">
  <div class="navbar">
  <div class="logo"><a href="#">Tools of Gold</a></div>
  <ul>
    <li><a href="#">About Us</a></li>
    <li><a href="#">Gallery</a></li>
    <li><a href="#">Products</a></li>
    <li><a href="#">Milestones</a></li>
    <li><a href="page2.html" target="_blank">Reach Us</a></li>
    <button><a href="#">Log In</a></button>
  </ul>
  </div></div><br>
  <!-- Mid Section -->
  <div>
    <div class="bigtext edu-au-vic-wa-nt-hand-aabb">Tools of Gold</div><br>
    <div class="subhead playwrite-be-vlg-aabb">We are one of the largest manufacturers of tools - from plumbing to mining.</div><br>
    <div class="tour rajdhani-medium">
      <button>Begin Tour</button>
    </div>
  </div>
</body>
</html>
```

### homrpage.css

The CSS file `homrpage.css` should contain styles for the HTML elements to ensure proper layout and design. Below is an example structure for the CSS file:

```css
/* homrpage.css */

body {
  font-family: 'Rajdhani', sans-serif;
  margin: 0;
  padding: 0;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  background-color: #333;
}

.navbar .logo a {
  color: #fff;
  text-decoration: none;
  font-size: 1.5rem;
}

.navbar ul {
  list-style: none;
  display: flex;
  margin: 0;
  padding: 0;
}

.navbar ul li {
  margin: 0 1rem;
}

.navbar ul li a {
  color: #fff;
  text-decoration: none;
}

.navbar button a {
  color: #333;
  background-color: #fff;
  padding: 0.5rem 1rem;
  text-decoration: none;
  border: none;
  border-radius: 5px;
}

.bigtext {
  font-family: 'Edu AU VIC WA NT Hand', cursive;
  font-size: 2.5rem;
  text-align: center;
  margin-top: 2rem;
}

.subhead {
  font-family: 'Playwrite BE VLG', sans-serif;
  font-size: 1.2rem;
  text-align: center;
  margin-top: 1rem;
}

.tour button {
  display: block;
  margin: 2rem auto;
  padding: 0.5rem 1rem;
  background-color: #333;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
```

## Getting Started

### Prerequisites

To view or edit this project, you need a web browser and a text editor.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/tools-of-gold-homepage.git
    ```
2. Navigate to the project directory:
    ```sh
    cd tools-of-gold-homepage
    ```

### Usage

1. Open the `index.html` file in your web browser to view the webpage:
    ```sh
    open index.html
    ```
   Alternatively, you can double-click the `index.html` file in your file explorer.

2. To edit the webpage, open `index.html` and `homrpage.css` in your preferred text editor.

## Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are reviewed and merged when appropriate.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'Add my feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a pull request
