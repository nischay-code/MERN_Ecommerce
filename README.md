# 🚀 MERN Stack eCommerce Site

This is a MERN stack eCommerce site built using the following technologies:

## 🌟 Frontend Dependencies
- 🧩 antd: ^5.1.7
- 🌐 axios: ^1.2.5
- ⚛️ react: ^18.2.0
- 🖼️ react-dom: ^18.2.0
- 🪖 react-helmet: ^6.1.0
- 🔥 react-hot-toast: ^2.4.0
- 🔗 react-router-dom: ^6.7.0
- 🛠️ react-scripts: 5.0.1
- 🍞 react-toastify: ^9.1.1
- 📈 web-vitals: ^2.1.4

## 🔧 Backend Dependencies
- 🔒 bcrypt: ^5.1.0
- 🎨 colors: ^1.4.0
- 🕒 concurrently: ^7.6.0
- 🌍 cors: ^2.8.5
- 🗂️ dotenv: ^16.0.3
- 🚂 express: ^4.18.2
- 📑 express-formidable: ^1.2.0
- 🔐 jsonwebtoken: ^9.0.0
- 🗄️ mongoose: ^6.8.4
- 📜 morgan: ^1.10.0
- 🔄 nodemon: ^2.0.20
- 🎨 react-icons: ^4.7.1
- 📝 slugify: ^1.6.5

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
  "server": "cd backend && npm start",
  "client": "cd frontend && npm start",
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
