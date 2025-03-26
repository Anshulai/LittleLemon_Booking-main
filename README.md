# Little Lemon Booking System

A restaurant table booking and management system for Little Lemon restaurant. This system allows customers to make reservations and helps staff manage bookings efficiently.

## Features

- Table reservation system
- Real-time booking availability
- User registration and authentication
- Booking management interface
- Email confirmation system
- Table layout visualization

## Technologies Used

- Frontend: React.js
- Backend: Node.js/Express.js
- Database: MongoDB
- Authentication: JWT
- Email Service: NodeMailer
- Styling: CSS3 with Sass

## Installation

1. Clone the repository:
```bash
git clone git@github.com:Anshulai/LittleLemon_Booking-main.git
```

2. Install dependencies:
```bash
cd LittleLemon_Booking
npm install
```

3. Set up environment variables:
- Create a `.env` file in the root directory
- Add necessary environment variables:
  ```
  PORT=3000
  MONGODB_URI=your_mongodb_connection_string
  JWT_SECRET=your_jwt_secret
  EMAIL_SERVICE=your_email_service
  EMAIL_USER=your_email
  EMAIL_PASS=your_email_password
  ```

4. Start the development server:
```bash
npm run dev
```

## Usage

1. **Customer Booking:**
   - Visit the website
   - Select date and time
   - Choose table preference
   - Fill in contact details
   - Confirm booking

2. **Admin Management:**
   - Login to admin dashboard
   - View all bookings
   - Manage reservations
   - Update table availability
   - Generate reports

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any queries or support, please contact:
hiro92012@gmail.com
