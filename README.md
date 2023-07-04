# ReserveSpace - Online Parking Reservation System

ReserveSpace is a web-based parking reservation system built using Django and Python. It allows users to reserve parking spaces online and integrates with the M-Pesa payment gateway for secure and convenient transactions.

## Features

- User Registration and Authentication: Users can create an account, log in, and manage their reservations.
- Parking Space Availability: Display real-time availability of parking spaces for users to select from.
- Reservation Management: Users can view, edit, and cancel their parking reservations.
- M-Pesa Integration: Seamless integration with the M-Pesa payment gateway for secure and convenient transactions.
- Admin Dashboard: An admin dashboard is provided for managing parking spaces, user accounts, and reservations.

## Installation

To run the ReserveSpace application locally, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/your-username/reservespace.git
   ```

2. Navigate to the project directory:

   ```
   cd reservespace
   ```

3. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Set up the database:

   ```
   python manage.py migrate
   ```

5. Start the development server:

   ```
   python manage.py runserver
   ```

6. Access the application by visiting `http://localhost:8000` in your web browser.

Note: Make sure you have Python and Django installed on your system before proceeding with the above steps.

## Configuration

Before running the application, you need to configure the M-Pesa integration. Follow these steps:

1. Obtain M-Pesa API credentials from Safaricom.

2. Update the configuration settings in the `settings.py` file:

   ```python
   # M-Pesa Configuration
   MPESA_CONSUMER_KEY = 'your_consumer_key'
   MPESA_CONSUMER_SECRET = 'your_consumer_secret'
   MPESA_SHORTCODE = 'your_shortcode'
   MPESA_PASSKEY = 'your_passkey'
   ```

3. Customize other settings in the `settings.py` file as per your requirements (e.g., database configuration, email settings).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the existing coding style and conventions.

