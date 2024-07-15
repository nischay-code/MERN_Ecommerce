# 🚀 MERN Stack eCommerce Site

This is a MERN stack eCommerce site built using the following technologies:

## 🌟 Frontend Dependencies
- 🧩 antd
- 🌐 axios
- ⚛️ react: 
- 🖼️ react-dom
- 🪖 react-helmet
- 🔥 react-hot-toast
- 🔗 react-router-dom
- 🛠️ react-scripts
- 🍞 react-toastify
- 📈 web-vitals

## 🔧 Backend Dependencies
- 🔒 bcrypt
- 🎨 colors
- 🕒 concurrently
- 🌍 cors
- 🗂️ dotenv
- 🚂 express
- 📑 express-formidable
- 🔐 jsonwebtoken
- 🗄️ mongoose
- 📜 morgan
- 🔄 nodemon
- 🎨 react-icons
- 📝 slugify

## 🛠️ Environment Variables

### Backend
Create a `.env` file in the root of the backend directory and add the following variables:
```bash
PORT=
DEV_MODE=
MONGO_URL=
JWT_SECRET=
```
### Frontend
Create a `.env` file in the root of the frontend directory and add the following variable:
```shell
REACT_APP_API=
```
## Installation

### Clone the Repository
```
git clone git@github.com:nischay-code/MERN_Ecommerce.git
cd MERN_Ecommerce
```

### Install Frontend Dependencies
```
cd frontend
npm install
```

### Install Backend Dependencies
```
cd ../backend
npm install
```

## 🚀 Running the Application

### Start the Backend Server
```
cd backend
npm run server
```

### Start the Frontend Server
```
cd ../frontend
npm start
```
## Adding the Development Command
### In the root package.json file, add the following script to run both the frontend and backend servers concurrently:
```
"scripts": {
    "start": "node server.js",
    "server": "nodemon server.js",
    "client": "npm start --prefix ./client",
    "dev": "concurrently \"npm run server\" \"npm run client\""
}
```
## Running the Application
### Start the Development Server
To start both the backend and frontend servers concurrently, run the following command from the root directory:

```shell
npm run dev
```
## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License.

Happy coding! 🎉
