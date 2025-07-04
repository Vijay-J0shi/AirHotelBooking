
# AirHotelBooking

**Live Website**: [https://arhotelbooking.onrender.com](https://arhotelbooking.onrender.com)

<br/>

<img width="531" alt="AirHotelBooking Demo" src="https://github.com/user-attachments/assets/1d42c109-cac1-4e30-92ee-e424bca1277c" />

---

## Tech Stack

* **Frontend**: React, Tailwind CSS
* **Backend**: Node.js, Express.js, MongoDB
* **Authentication**: JWT
* **Image Upload**: Cloudinary
* **Deployment**: Render

---

## Features

* User authentication (Register, Login) using JWT
* Create, edit, and manage property listings
* Booking system with integrated date picker
* Secure image uploads using Cloudinary
* Fully responsive UI for mobile and desktop
* Deployed using Render for both frontend and backend

---

## Local Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AirHotelBooking.git
cd AirHotelBooking
```

### 2. Install Dependencies

#### Frontend

```bash
cd frontend
npm install
```

#### Backend

```bash
cd ../backend
npm install
```

---

### 3. Create `.env` File in Backend

Inside the `/backend` directory, create a `.env` file and add the following variables:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

> Replace each placeholder with your actual configuration values.

---

### 4. Run the Application

#### Start Backend

```bash
cd backend
npm run dev
```

#### Start Frontend

```bash
cd frontend
npm run dev
```

Open your browser at [http://localhost:5173](http://localhost:5173) to view the application.

---

## Project Structure

```
AirHotelBooking/
│
├── frontend/                # React frontend
│   ├── src/
│   ├── index.html
│   ├── tailwind.config.js
│   └── ...
│
├── backend/                 # Express backend
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── model/
│   ├── routes/
│   ├── index.js
│   └── ...
│
├── .gitignore
├── README.md
└── ...
```

---

## Deployment

This project is deployed on **Render**. Both frontend and backend are hosted as separate services.
Add your environment variables to the backend service's settings in Render.

---

## Contributing

Open to contributions, bug reports, and feature suggestions via issues or pull requests.

---

## License

This project is licensed under the MIT License.

