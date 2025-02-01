# Hotel Booking System

This is a hotel booking system built with PHP and JavaScript. The system allows users to browse available rooms, make bookings, and manage their reservations. Administrators can manage hotels, rooms, and bookings through an admin panel.

## Project Structure

Workspace
(rerun without)
Collecting workspace information

Sure, here is the updated README.md file:

.DS_Store 404.php about.php admin-panel/ admins/ bookings-admins/ hotels-admins/ index.php layouts/ rooms-admins/ styles/ auth/ login.php logout.php register.php config/ config.php contact.php includes/ footer.php header.php index.php js/ .DS_Store bootstrap-datepicker.js bootstrap.min.js google-map.js jquery-3.2.1.min.js jquery-migrate-3.0.1.min.js jquery.animateNumber.min.js jquery.easing.1.3.js ... README.md rooms/ pay.php room-single.php rooms.php services.php users/



## Features

- **User Authentication**: Users can register, log in, and log out.
- **Room Booking**: Users can browse available rooms, view room details, and make bookings.
- **Admin Panel**: Administrators can manage hotels, rooms, and bookings.
- **Contact Form**: Users can contact the hotel through a contact form.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/NahomKeneni/hotel_booking_system.git
    ```

2. Navigate to the project directory:
    ```sh
    cd hotel-booking
    ```

3. Set up the database:
    - Import the SQL file located in the `database` directory into your MySQL database.
    - Update the database configuration in [config.php](http://_vscodecontentref_/18).

4. Start the server:
    ```sh
    php -S localhost:8000
    ```

5. Open your browser and navigate to `http://localhost:8000`.

## Usage

### User

- **Register**: Navigate to the register page and create an account.
- **Login**: Log in with your credentials.
- **Browse Rooms**: View available rooms and their details.
- **Make a Booking**: Select a room and make a booking.
- **Manage Bookings**: View and manage your bookings.

### Admin

- **Login**: Log in to the admin panel.
- **Manage Hotels**: Add, update, and delete hotels.
- **Manage Rooms**: Add, update, and delete rooms.
- **Manage Bookings**: View and manage all bookings.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions, please contact me at nahomkeneni4@gmail.com .