# SUSTAINIFY - Scrap Recycling Platform

**SUSTAINIFY** is an innovative scrap recycling website that enables users to conveniently schedule pickups for their scrap materials. The platform bridges the gap between users, admin, and pickup personnel, making the recycling process streamlined and hassle-free.

---

## 🚀 Project Overview
**SUSTAINIFY** aims to:
1. **Simplify Scrap Management**: Allow users to schedule pickups for scrap materials at their convenience.
2. **Enhance Transparency**: Provide real-time scrap price calculations for users.
3. **Manage Roles Efficiently**: Enable seamless management of tasks for admins and pickup personnel.

The platform has **three primary user roles**:
- **Admin**: Manage overall operations.
- **Pickup Personnel**: View pickup requests and fulfill them.
- **Normal User**: Schedule pickups and view scrap prices.

---

## 💻 Features
### 1. **User Role-Based Functionalities**
- **Admin**:
  - Manage users and pickup requests.
  - Monitor completed and pending scrap collections.
- **Pickup Personnel**:
  - View assigned pickup schedules.
  - Update task statuses (e.g., "In Progress", "Completed").
- **Normal User**:
  - Schedule pickups for scrap materials.
  - View real-time scrap prices using the **Price Calculator**.

### 2. **Scrap Price Calculator**
Users can calculate the prices of scrap materials based on their type and weight. This feature ensures price transparency and helps users make informed decisions.

### 3. **Convenient Scheduling**
Users can schedule pickups at their convenience, selecting dates and times that suit them.

### 4. **Dynamic Dashboard**
Each role has a custom dashboard with insights and functionalities tailored to their needs:
- **Admins**: Comprehensive management overview.
- **Pickup Personnel**: List of pickup tasks and their statuses.
- **Users**: Upcoming and past pickups with tracking information.

---

## 🔧 Tech Stack
The project is built using the following technologies:
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB

---

## ⚙️ Setup Instructions
Follow these steps to set up and run the project locally:

### Prerequisites
- Node.js and npm installed on your system.
- MongoDB installed or access to a cloud MongoDB database.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AshishKapishwey/sustainify.git
   cd sustainify
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     PORT=3000
     MONGODB_URI=your_mongodb_connection_string
     ```

4. Start the server:
   ```bash
   npm start
   ```

5. Open the application in your browser:
   ```
   http://localhost:3000
   ```

---

## 📂 Folder Structure
```
SUSTAINIFY/
│
├── public/          # Static files
├── src/             # Source code
│   ├── models/      # Database models
│   ├── routes/      # API routes
│   ├── controllers/ # Request handlers
│   ├── views/       # Frontend templates
│   └── utils/       # Utility functions
│
├── .env             # Environment variables
├── package.json     # Dependencies and scripts
└── README.md        # Project documentation
```

---

## 🤝 Contributing
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Commit your changes and push to your fork.
4. Submit a pull request.


---

## 🌟 Acknowledgements
A big thank you to everyone who contributed to the project and provided feedback!
