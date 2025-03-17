# Yoom
## Images of frontend
![Screenshot 2025-03-17 224728](https://github.com/user-attachments/assets/aa461398-1302-4841-a762-654295dc4ae5)
![Screenshot 2025-03-17 224720](https://github.com/user-attachments/assets/7250155e-bea7-4b89-814c-105f8e100fca)
![Screenshot 2025-03-17 224711](https://github.com/user-attachments/assets/de710642-677e-4778-acf2-c07bd88a0d0f)

Yoom is a web application built with Next.js that provides video conferencing capabilities.

## Features

- Real-time video conferencing
- User authentication with Clerk
- Stream API integration for communication features

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn

### Installation

1. Clone the repository - git clone https://github.com/hardiksharma23/Yoom.git cd Yoom

2. Install dependencies - npm install
    

3. Set up environment variables
Create a `.env.local` file in the root directory with the following variables:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key

Run the development server - npm run dev or yarn dev

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Technologies Used

- [Next.js](https://nextjs.org/)
- [Clerk](https://clerk.dev/) for authentication
- [Stream API](https://getstream.io/) for real-time communication

## License

[MIT](LICENSE)

## Contact

Hardik Sharma - [GitHub](https://github.com/hardiksharma23)
