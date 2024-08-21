# Info-site

# Full Stack Developer Roadmap

This project demonstrates a simple Express server in Node.js that serves different pages about the Full Stack Developer Roadmap. It includes handling for `index.html`, `about.html`, `contact-me.html`, and a custom `404.html` for any undefined routes.

## Project Structure

```
project-directory/
│
├── index.js
├── index.html
├── about.html
├── contact-me.html
└── 404.html
```

## Description

- **Home Page (`index.html`)**: An overview of the Full Stack Developer Roadmap.
- **About Page (`about.html`)**: Detailed information about the roadmap and its components.
- **Contact Page (`contact-me.html`)**: A form or contact details for visitors to get in touch regarding the roadmap.
- **404 Page (`404.html`)**: Custom 404 error page shown when a user navigates to an undefined route.

## How to Run

1. **Navigate to the project directory:**

   ```sh
   cd project-directory
   ```

2. **Start the server:**

   ```sh
   node index.js
   ```

3. **Open your browser and navigate to the following URLs:**
   - `http://localhost:8080` to view the home page
   - `http://localhost:8080/about` to view the about page
   - `http://localhost:8080/contact-me` to view the contact page

Undefined routes will display the custom `404.html` page.
