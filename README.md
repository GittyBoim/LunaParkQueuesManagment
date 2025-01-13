Queue Management App for Amusement Parks
Description
This is a native mobile application designed to manage queues in amusement parks. The app aims to solve the problem of long wait times by allowing visitors to register for rides and receive push notifications when it’s time to board. It provides a real-time queue management system that enhances user experience by reducing waiting time.

Native Application: Built using React Native for cross-platform mobile support.
Real-Time Notifications: Push notifications are managed through Firebase, notifying users a few minutes before their turn arrives.
Queue Registration: Users can register for rides and manage their waiting time effectively.
Backend: Built with NestJS and Node.js for handling REST API calls and managing business logic.
Features
Register for rides and attractions at the park.
Receive notifications when your turn is coming up.
Real-time queue status and updates.
User-friendly mobile interface built with React Native.
Firebase-powered notifications for accurate time updates.
Tech Stack
Frontend (Client): React Native
Backend (Server): Node.js with NestJS framework
Database: MySQL
Notifications: Firebase Cloud Messaging (FCM)
State Management: Redux (for managing data across the app)
Installation
Prerequisites
Before getting started, make sure you have the following installed:

Node.js (v12 or above)
MySQL (for the database)
Firebase Project (for push notifications)
Setup Instructions
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/queue-management-app.git
cd queue-management-app
Install the dependencies for the client and server:

Client (React Native)

bash
Copy code
cd client
npm install
Server (NestJS)

bash
Copy code
cd server
npm install
Set up your Firebase project and configure Firebase Cloud Messaging in the app.

Configure your MySQL database and ensure the proper environment variables are set in the .env file.

Run the client and server applications:

Client

bash
Copy code
npm start
Server

bash
Copy code
npm run start
Open the app on your mobile device/emulator to test the functionality.

Usage
Launch the app and register for rides in the amusement park.
You will receive push notifications before it's your turn to board.
Monitor your waiting time and stay updated on the queue status.
Contributing
Contributions are welcome! If you want to improve the app, feel free to fork the repository, make changes, and submit a pull request.

License
Distributed under the MIT License. See LICENSE for more information.
