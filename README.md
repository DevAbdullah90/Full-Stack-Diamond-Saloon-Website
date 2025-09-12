# Diamond Salon - Modern Salon & Spa Website

A full-stack salon and spa booking website built with Next.js, featuring online booking, payment processing, and user authentication.

## 🌟 Features

- **Modern UI/UX Design**
  - Responsive layout for all devices
  - Smooth animations with Framer Motion
  - Custom fonts (Geist) for enhanced typography
  - Tailwind CSS for styling

- **Online Booking System**
  - Service selection and scheduling
  - Real-time availability checking
  - Booking confirmation system
  - Stripe payment integration

- **User Authentication**
  - Secure user registration and login
  - JWT-based authentication
  - Password encryption with bcrypt

- **Contact & Communication**
  - Contact form with email notifications
  - SendGrid integration for reliable email delivery
  - Professional inquiry handling

- **Admin Features**
  - Booking management
  - User management
  - Service management
  - Team member profiles

## 🚀 Tech Stack

- **Frontend:**
  - Next.js 14
  - React 18
  - TypeScript
  - Tailwind CSS
  - Framer Motion
  - Stripe Elements

- **Backend:**
  - Next.js API Routes
  - MongoDB with Mongoose
  - Stripe API
  - SendGrid/Nodemailer

- **Authentication & Security:**
  - JWT (JSON Web Tokens)
  - bcrypt.js
  - Secure HTTP-only cookies

## 📦 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v18 or higher)
- npm or yarn
- MongoDB instance
- Stripe account (for payments)
- SendGrid account (for emails)

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone [your-repo-url]
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:
   Create a `.env.local` file with the following variables:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
   SENDGRID_API_KEY=your_sendgrid_api_key
   ```

4. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) to view the application

## 📚 Project Structure

- `/app` - Next.js 14 app directory
  - `/api` - API routes for backend functionality
  - `/components` - Reusable React components
  - `/models` - MongoDB/Mongoose models
  - `/lib` - Utility functions and configurations

## 🔧 Available Scripts

- `npm run dev` - Runs the development server
- `npm run build` - Builds the application for production
- `npm start` - Runs the built application
- `npm run lint` - Runs ESLint for code quality

## 🌐 Deployment

The application can be deployed on Vercel:

1. Push your code to a Git repository
2. Import the project to Vercel
3. Configure environment variables
4. Deploy!

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

For any queries or support, please contact [Your Contact Information]
