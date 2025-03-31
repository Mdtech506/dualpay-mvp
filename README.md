# DualPay MVP

DualPay MVP is a payment solution that combines XRP and Fiat payment capabilities, offering a seamless dual-currency payment experience.

## Prerequisites

Before running the application, make sure you have the following installed:

1. Node.js (v14 or higher)
2. MongoDB Community Server
3. npm (usually comes with Node.js)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Mdtech506/dualpay-mvp.git
cd dualpay-mvp
```

2. Install dependencies:
```bash
npm install
```

3. Set up MongoDB:
- Install MongoDB Community Server from https://www.mongodb.com/try/download/community
- Make sure MongoDB is running on the default port (27017)

4. Configure environment variables:
- Copy `.env.example` to `.env` (if not present)
- Update the following variables in `.env`:
  ```
  MONGODB_URI=mongodb://localhost:27017/dualpay
  JWT_SECRET=your-super-secret-key-change-in-production
  SESSION_SECRET=your-session-secret-change-in-production
  ```

## Running the Application

1. Start MongoDB service (if not already running)

2. Start the application:
```bash
npm start
```

3. Access the application:
- Open your web browser and navigate to `http://localhost:3000`
- The login page will be displayed
- Register a new account to get started

## Features

- User Authentication with 2FA
- KYC Verification
- XRP Wallet Management
- Fiat Wallet Management
- QR Code Payment Support
- Real-time Transaction Updates
- Biometric Authentication Support
- Point of Sale (POS) Interface

## Security Notes

- Change all secret keys in production
- Enable HTTPS in production
- Keep your MongoDB instance secure
- Never share your API keys or tokens

## Development

To run the application in development mode with auto-reload:
```bash
npm run dev
```

## Support

For any issues or questions, please open an issue in the GitHub repository.
