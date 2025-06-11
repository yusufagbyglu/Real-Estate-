# Real Estate Web Application

A modern, full-stack real estate listing platform built with Next.js, featuring property listings, search functionality, and user authentication.

## 🚀 Features

- 🔍 Property search with filters
- 🏠 Property details and image galleries
- 👤 User authentication with AWS Cognito
- 📍 Interactive map view with Mapbox
- 📱 Responsive design for all devices
- ⚡ Fast performance with Next.js

## 🛠️ Tech Stack

- **Frontend**: Next.js, React, TypeScript, Tailwind CSS
- **Maps**: Mapbox
- **Authentication**: AWS Cognito
- **State Management**: React Context API
- **Styling**: Tailwind CSS

## 📁 Project Structure

```
real-estate-nextjs/
├── client/                 # Frontend Next.js application
├── server/                 # Backend API (if applicable)
├── public/                 # Static files
└── .env.example           # Example environment variables
```

## 🚀 Getting Started

### Prerequisites

- Node.js 16.8 or later
- npm or yarn
- Mapbox Access Token
- AWS Cognito Configuration

### Installation

1. Clone the repository:
   ```bash
   git clone [your-repository-url]
   cd real-estate-nextjs
   ```

2. Install dependencies:
   ```bash
   cd client
   npm install
   # or
   yarn
   ```

3. Set up environment variables:
   - Copy `.env.example` to `.env.local` in the client directory
   - Fill in your environment variables:
     ```
     NEXT_PUBLIC_API_BASE_URL=http://localhost:3001
     NEXT_PUBLIC_MAPBOX_ACCESS_TOKEN=your_mapbox_token
     NEXT_PUBLIC_AWS_COGNITO_USER_POOL_ID=your_user_pool_id
     NEXT_PUBLIC_AWS_COGNITO_USER_POOL_CLIENT_ID=your_client_id
     ```

4. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint
- `npm test` - Run tests

## 🌐 Environment Variables

Create a `.env.local` file in the client directory with the following variables:

```
NEXT_PUBLIC_API_BASE_URL=your_api_url
NEXT_PUBLIC_MAPBOX_ACCESS_TOKEN=your_mapbox_token
NEXT_PUBLIC_AWS_COGNITO_USER_POOL_ID=your_user_pool_id
NEXT_PUBLIC_AWS_COGNITO_USER_POOL_CLIENT_ID=your_client_id
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Maps by [Mapbox](https://www.mapbox.com/)
- Authentication with [AWS Cognito](https://aws.amazon.com/cognito/)
