---

# 🎨 Tee Designer: Create Your Custom T-Shirts

# [tee-designer.mukulsai.com](https://tee-designer.mukulsai.com/)

Welcome to **Tee Designer**, a fun and interactive platform for creating personalized t-shirt designs! Design your dream t-shirt with custom logos, AI-generated patterns, and more. 🚀

---

## ✨ Features

- 🖌️ **Custom T-Shirt Designer**: Upload images, add text, and create your unique designs.
- 🤖 **AI-Powered Creativity**: Use OpenAI's DALL-E API to generate logos and patterns.
- ⚡ **Real-Time Editing**: Drag, resize, and rotate your designs effortlessly.
- 🌐 **Responsive UI**: Optimized for all devices with Tailwind CSS.
- 🚀 **Blazing-Fast**: Built with Vite for a seamless development experience.

---
## 🏗️ Project Architecture

### Frontend (Tee Designer App)
- **Tech Stack**: React.js, Vite, Tailwind CSS
- **Description**: Provides a responsive and interactive UI for designing t-shirts with custom logos and patterns. It also integrates OpenAI DALL-E API for AI-generated designs.
- **Repository**: [Frontend Repo](https://github.com/MukulSaiPendem/tee-designer)

### Backend (Tee Designer Server)
- **Tech Stack**: Node.js, Express.js
- **Description**: Handles API requests, stores user-uploaded designs, and communicates with external services like OpenAI.
- **Repository**: [Backend Repo](https://github.com/MukulSaiPendem/tee-designer-server)

---

## 🔧 Technologies

| Technology    | Description                             |
|---------------|-----------------------------------------|
| ⚛️ React.js   | Component-based UI development.         |
| 🌀 Tailwind CSS | Utility-first framework for responsive styling. |
| 🛠️ Vite       | Fast and optimized development build.   |
| 🧠 OpenAI DALL-E | AI-powered logo and pattern generation. |

---

## 🛠️ Getting Started

Follow these steps to run the project locally:

### 📋 Prerequisites

Ensure you have the following installed:

- Node.js (version 14 or higher) 🌟
- npm or yarn 📦

### ⚙️ Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/tee-designer.git
   cd tee-designer
   ```

2. Install dependencies:  
   ```bash
   npm install
   ```

3. Start the development server:  
   ```bash
   npm run dev
   ```

4. Open your browser and visit:  
   🌐 `http://localhost:3000`

---

## 🔄 Integration Between Frontend and Backend

1. Start both the frontend and backend servers:
   - Frontend runs on `http://localhost:3000`
   - Backend runs on `http://localhost:5000` 
   
2. Update the frontend configuration (e.g., `src/config.js`) to point to the backend API URL:
   ```javascript
   export const API_URL = 'http://localhost:5000';
   ```

3. Ensure the backend server is running before interacting with the frontend.

---


## 📂 Project Structure

```
tee-designer/
├── public/           # Static assets
├── src/              # Source code
│   ├── components/   # Reusable UI components
│   ├── assets/       # Images and icons
│   ├── styles/       # Global and component-specific styles
├── package.json      # Dependencies and scripts
├── tailwind.config.js# Tailwind configuration
└── vite.config.js    # Vite configuration
```

---

## 🚀 How to Use

1. 👕 **Pick Your Base**: Choose a t-shirt color and style.
2. 🖼️ **Add Designs**: Upload your logo or generate AI-powered designs.
3. ✍️ **Customize**: Drag, resize, and rotate your design on the t-shirt.
4. 📤 **Save & Share**: Save your design and show it to the world!

---

## 🌟 Future Enhancements

- 👚 Add support for hoodies, hats, and other apparel.
- 💾 Enable user accounts for saving designs.
- 🛒 Integrate payment options for ordering custom t-shirts.

---

## 🤝 Contributing

We ❤️ contributions! Here's how you can get involved:

1. Fork the repo 🍴
2. Create your branch: `git checkout -b feature/awesome-feature` 🌿
3. Commit your changes: `git commit -m "Add awesome feature"` 📝
4. Push to the branch: `git push origin feature/awesome-feature` 🚀
5. Open a pull request! 🎉

---

## 💬 Contact

Have questions or feedback? Feel free to reach out! 😊  
📧 Email: [pendem.mu@northeastern.edu](mailto:pendem.mu@northeastern.edu)  

<!--🌐 Website: [Your Portfolio](https://yourportfolio.com)  -->

---
