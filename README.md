# NITC Event Manager

The NITC Event Manager is a streamlined digital permission system designed to simplify the process of requesting and approving permissions for various facilities at NIT Calicut (NITC). This system enables students to submit permission requests, allows faculty advisors to approve or deny requests, and provides an admin dashboard for managing and monitoring all activities.

## Features

### Student Features
- **Request Form**: A structured form for students to submit permission requests (e.g., venue booking, bus service, equipment reservation).
- **Request Categories**: Options to select different types of permissions.
- **Document Upload**: Facility to upload required documents for requests.
- **Real-time Status Tracking**: Students can track the status of their requests (Pending, Approved, Denied).
- **History and Notifications**: Log of past requests and real-time notifications for updates.

### Faculty Features
- **Approval Dashboard**: View and manage pending requests by category.
- **Decision Panel**: Approve, deny, or request additional information for requests.
- **Comments Section**: Add comments or suggestions for each request.
- **Notification System**: Notify students about approval, denial, or requests for further information.

### Admin Features
- **Request Management**: View and manage all requests across departments with filters by type, status, and faculty advisor.
- **User Roles**: Assign and manage roles (e.g., student, faculty advisor, admin) with respective permissions.
- **Audit Logs**: Track all actions taken in the system for accountability and auditing.
- **Reports and Analytics**: Generate reports on request statistics, approval rates, and common request types.
- **Notification Settings**: Configure and customize notifications for different user types.

### System Features
- **User Authentication**: Secure login system with role-based access control.
- **Responsive Design**: Accessible on desktops, tablets, and mobile devices.
- **Search and Filters**: Quick access to specific requests using search and filter functionality.
- **Integration with College Systems**: Ability to integrate with existing college portals or student databases.

---
 
---

## Technologies Used

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Real-time Notifications**: Socket.io (optional, based on implementation)

---

## Setup Instructions

### Backend Setup
1. Navigate to the `backend` directory:
   ```bash
   cd backend
2. Install dependencies:
   ```bash
   npm install
3. Create a .env file in the backend directory with the following variables:
   ```bash
   MONGO_URI=
   port=
   SECRET_KEY=
   FRONTEND_URL=
   MAILER_SEND_API_KEY=
4. Start the server:
   ```bash
   npm start


### Frontend Setup
1. Then run the frontend:
   ```bash
   cd frontend
   <!-- if you are using yarn    -->
   yarn install
   yarn start  

   <!-- if you are using npm -->
   npm install
   npm start  


## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch for your feature or bugfix
3. Commit your changes
4. Submit a pull request


## Contact

For any queries or feedback, please contact:

Email: hsai19172@gmail.com





