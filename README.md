# Subscriber Portal with Admin Panel

A responsive web application for managing internet subscribers, including user authentication, package management, and data usage tracking.

## Features

- **User Authentication**
  - Phone number login with country code support
  - New user registration with form validation
  - Session management

- **Dashboard**
  - Overview of account status
  - Data usage statistics
  - Active devices tracking
  - Recent activity feed

- **Package Management**
  - View available internet packages
  - Purchase new packages
  - Track active subscriptions

- **Voucher System**
  - Activate vouchers
  - Track voucher history
  - View voucher benefits

- **Usage Tracking**
  - Real-time data usage statistics
  - Historical usage charts
  - Device-wise usage breakdown

## Prerequisites

- Web browser (Chrome, Firefox, Safari, or Edge)
- Web server (for local development, you can use Live Server in VS Code or Python's built-in HTTP server)

## Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd subscriber-portal
   ```

2. **Run a local server**
   - Using Python (if installed):
     ```bash
     python -m http.server 8000
     ```
   - Or use the Live Server extension in VS Code

3. **Open in browser**
   - Visit `http://localhost:8000` in your web browser

## Demo Accounts

For testing purposes, you can use the following pre-registered phone numbers:
- +919876543210
- +919123456789
- +918888888888

Any other phone number will be treated as a new registration.

## Project Structure

```
subscriber-portal/
├── index.html          # Login page
├── register.html       # Registration page
├── dashboard.html      # Main dashboard
├── README.md           # This file
└── assets/             # Static assets (images, icons, etc.)
```

## Technologies Used

- HTML5, CSS3, JavaScript (ES6+)
- [Chart.js](https://www.chartjs.org/) - For data visualization
- [Font Awesome](https://fontawesome.com/) - For icons
- [intl-tel-input](https://github.com/jackocnr/intl-tel-input) - For phone number input with country codes

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Icons by [Font Awesome](https://fontawesome.com/)
- Charts by [Chart.js](https://www.chartjs.org/)
- Phone number input by [intl-tel-input](https://github.com/jackocnr/intl-tel-input)
