# 📝 Blog

Welcome to my personal blog! This project is a reflection of my thoughts, ideas, and experiences. Please note that this is a personal project, and each post is written and published by me alone—without review by any team. Some of the content may extend beyond my formal studies, but driven by a passion for learning and a lifelong learner mindset, I write about what interests or fascinates me.


## 🌟 Features

- **Responsive Design**: Optimized for all devices to ensure a great user experience.
- **Markdown Support**: Write blog posts effortlessly using Markdown.
- **Tagging & Categories**: Organize posts with tags and categories for easy navigation.
- **Search Functionality**: Quickly find posts with a powerful search feature.
- **Commenting System**: Engage with readers through a built-in commenting feature.
- **SEO Optimized**: Posts are optimized for better visibility on search engines.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed before starting:

- [PHP](https://www.php.net/) >= 8.0
- [Composer](https://getcomposer.org/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- [MySQL](https://www.mysql.com/) or any other database supported by Laravel

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-blog-repo.git
    ```
2. Navigate to the project directory:

    ```bash
   cd your-blog-repo
    ```
3. Install PHP dependencies:

    ```bash
    composer install
    ```
4. Install Node.js dependencies:
    ```bash
    npm install
    ```
    or 
    ```bash
    yarn install
    ```
5. Create a copy of the `.env` file:

    ```bash
    cp .env.example .env
    ```
6. Generate the application key:

    ```bash
    php artisan key:generate
    ```
7. Set up your database in the .env file, then run migrations:
    ```bash
    php artisan migrate
    ```
8. Install and build front-end assets:

    ```bash
    npm run build
    ```
    or 
    ```bash
    yarn build
    ```
### Running the Blog
To start the local development server:

```bash
php artisan serve
```

Visit **http://localhost:8000** to view your blog in the browser.

## 📂 Project Structure
Here’s an overview of the project structure:

```
├── app/                # Application code
├── config/             # Configuration files
├── database/           # Migrations and seeders
├── public/             # Public assets (images, JS, CSS)
├── resources/          # Views, Blade templates, and assets
│   ├── css/            # CSS stylesheets
│   ├── js/             # JavaScript files
│   ├── views/          # Blade templates
├── routes/             # Application routes
├── storage/            # File storage
├── tests/              # Unit and feature tests
├── .env                # Environment configuration
├── .gitignore          # Git ignore file
├── composer.json       # PHP dependencies and project metadata
├── package.json        # Node.js dependencies and scripts
└── README.md           # Project documentation

```

## 🎨 Customization

Feel free to customize the blog’s appearance and functionality. Modify the Blade templates, CSS, and JavaScript files in the resources directory to match your style.

## 🤝 Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## 🛡️ License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Contact
If you have any questions or suggestions, feel free to reach out:

Email: vireakrothpun@gmail.com

LinkedIn: VireakRoth Pun

Facebook: virak.roth.545