# 📦 Docker YouTube

> 🐳 Docker + ⚛️ React + 📹 YouTube Clone | Features: 🎥 Video Streaming, 🔍 Search, 📁 Upload, 🧠 Recommendations | Tools: Axios ⚡, Tailwind 🎨, Node.js 🌐, MongoDB 🍃

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

---

## 🚀 Available Scripts

In the project directory, you can run:

### `npm start`  
▶️ Starts the app in development mode.  
Visit: [http://localhost:3000](http://localhost:3000)

---

### `npm test`  
🧪 Runs the test runner in watch mode.  
[CRA test docs →](https://facebook.github.io/create-react-app/docs/running-tests)

---

### `npm run build`  
🏗 Builds the app for production into the `build/` folder.  
Optimized for best performance.  
[Deployment guide →](https://facebook.github.io/create-react-app/docs/deployment)

---

### `npm run eject`  
⚙️ Copies the config (Webpack, Babel, ESLint, etc.) into your project so you can customize.  
**Note**: Ejecting is permanent.

---

## 🐳 Docker Setup

To build and run with Docker:

```bash
# Build Docker image
docker build -t docker-youtube .

# Run container
docker run -p 3000:3000 docker-youtube
