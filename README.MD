# bs-ecommerce-theme-01

This project is a web page theme designed using **Bootstrap**, including HTML, CSS, and Sass for custom styling. The project follows a well-structured file organization to maintain clarity and scalability.

## Project Purpose

This project is created solely for educational and practice purposes. It is intended to help develop and demonstrate skills in web development using open-source technologies such as Bootstrap, Sass, fslightbox, and Font Awesome. All components and code within this repository are used as a learning tool and may not be fully optimized for production use.

The project is licensed under the [GNU General Public License v3.0](LICENSE.txt) and includes references to other open-source libraries with their respective licenses.

## Project Structure

The project's folder structure is as follows:

ecommerce-template/
├── css/
│ ├── bootstrap.css
│ ├── style.css

├── node_modules/

├── scss/
│ ├── \_bs-overrides.scss
│ ├── bootstrap.scss
│ ├── style.scss

├── public/
│ ├── img/
│ ├── index.html
│ ├── details.html

├── package-lock.json
├── package.json
└── README.md

## Technologies Used

- **Bootstrap**: Responsive design framework for CSS (https://getbootstrap.com/)
- **Sass**: CSS preprocessor to customize Bootstrap variables and add custom styles (https://sass-lang.com/)
- **fslightbox**: A lightweight lightbox library for image and gallery displays (https://fslightbox.com/)
- **Font Awesome**: Internet's icon library and toolkit, used by millions of designers, developers, and content creators (https://fontawesome.com/)

## Customization

To maintain the separation of Bootstrap's core styles and custom styles:

1. **Bootstrap Variables**: Override Bootstrap variables in `scss/bootstrap.scss` for consistent theme colors, such as `$primary`.
2. **Separate CSS Files**: Bootstrap’s core styles and your custom styles are compiled into separate CSS files. This way, the custom styles can be updated independently.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-project.git
   cd your-project
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Compile Sass files:
   ```bash
   npm run scss
   ```
4. Open public/index.html to view the project in the browser.
