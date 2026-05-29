# Module-9-Assessment-3 

# Mini Blog

Mini Blog is a simple front-end blog website built with **HTML**, **Bootstrap**, **JavaScript**, and **Font Awesome**.  
It loads blog posts from the IT Varsity Mini Blog API and allows filtering by category.

## Features

- View **All** posts
- View **Latest** posts
- View **Popular** posts
- Toggle **Dark Mode**
- Responsive layout using **Bootstrap**
- Icons provided by **Font Awesome**

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap
- Font Awesome
- Fetch API

## API Used

Posts are loaded from:

`https://mysite.itvarsity.org/api/mini-blog/`

## Project Structure

- `index.html` - main page
- `css/bootstrap.min.css` - Bootstrap styles
- `css/custom.css` - custom styles
- `js/jquery-4.0.0.min.js` - jQuery
- `js/bootstrap.bundle.min.js` - Bootstrap scripts
- `fontAwesome/css/all.css` - Font Awesome styles
- `img/` - images and logo

## How to Run

1. Open the project folder in **Visual Studio Code**
2. Make sure all required folders are present:
   - `css`
   - `js`
   - `img`
   - `fontAwesome`
3. Run the project with **Live Server** or open `index.html` in a browser

## How It Works

- When the page loads, `init()` runs
- The app connects to the Mini Blog API
- Clicking:
  - **All** loads all posts
  - **Latest** loads latest posts
  - **Popular** loads popular posts
- **Dark Mode** changes the page theme

## Notes

- Font Awesome is loaded locally from the project folder
- The project depends on the API being available online
- Images for posts are loaded from the API upload path

## Author

Tino Created for **Module 9 Assessment 3**
