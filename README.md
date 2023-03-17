# Laravel-Snort

Laravel-Snort is a web application that helps users monitor their network and stay informed about potential security threats. The project uses Laravel as a backend API and Angular as a frontend framework to display Snort log data to the user. By parsing Snort log files, the application can extract useful information such as the source and destination IP addresses, the type of attack detected, and other relevant data.

## Getting Started

To get started with Laravel-Snort, you'll need to have the following installed on your system:

- PHP 7.3+
- Composer
- Node.js
- NPM

Once you have these installed, follow these steps to get started:

1. Clone the repository to your local machine:

git clone https://github.com/your-username/laravel-snort.git

2. Install the required PHP packages:
composer install

3. Install the required NPM packages:
npm install

4. Create a new `.env` file from the example file:
cp .env.example .env

5. Generate a new application key:
php artisan key:generate

6. Update the `.env` file with your database credentials and other configuration settings.

7. Run database migrations to create the required tables:
php artisan migrate

8. Start the development server:
php artisan serve

The application should now be running on `http://localhost:8000`.

9. Start the Angular development server:
npm run start

The frontend application should now be running on `http://localhost:4200`.

## Usage

Once the application is up and running, you can use it to monitor your network and stay informed about potential security threats. The application will parse Snort log files and display useful information to the user, such as the source and destination IP addresses, the type of attack detected, and other relevant data.

## Contributing

If you'd like to contribute to Laravel-Snort, please fork the repository and submit a pull request. We're always looking for new features, bug fixes, and improvements to the application.

## License

Laravel-Snort is open source software licensed under the MIT license. See the LICENSE file for more information.
