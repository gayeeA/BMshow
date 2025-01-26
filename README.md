# BMshow

BMshow is a web application designed to provide users with information about movies. 

It offers features such as browsing movie listings, viewing details, and user authentication.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- Browse a list of movies.
- View detailed information about each movie.
- User authentication system.

## Installation

To set up the BMshow application locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/gayeeA/BMshow.git
   cd BMshow
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**

   ```bash
   python manage.py migrate
   ```

5. **Start the development server:**

   ```bash
   python manage.py runserver
   ```

6. **Access the application:**

   Open your browser and navigate to `http://127.0.0.1:8000/` to use the application.

## Usage

- **Browsing Movies:** On the homepage, users can browse the list of available movies.
- **Viewing Movie Details:** Click on a movie to view detailed information.
- **User Authentication:** Users can sign up and log in to access personalized features.

## Dependencies

The project relies on the following major dependencies:

- Django: A high-level Python web framework.
- SQLite: A lightweight database engine used for development.

For a complete list of dependencies, refer to the `requirements.txt` file in the repository.

## Contributing

Contributions are welcome! If you'd like to contribute to BMshow, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

Please ensure your code adheres to the project's coding standards and includes appropriate tests.

## License

BMshow is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

