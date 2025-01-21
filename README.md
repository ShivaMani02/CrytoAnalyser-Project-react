# CryptoAnalyser - Explore the World of Cryptocurrency

**CryptoAnalyser** is a React-based project designed to provide real-time information on cryptocurrencies using powerful APIs from [RapidAPI](https://rapidapi.com). This application is suitable for developers looking to master React.js and API integration while exploring the world of digital currencies.

## Demo
Check out the video tutorial on **Dev. Shivansh Vasu** channel:
- [YouTube Channel](https://www.youtube.com/@shivanshvasu/videos)

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup Instructions](#setup-instructions)
5. [Project Structure](#project-structure)
6. [Scripts](#scripts)
7. [API Integration](#api-integration)

## Introduction
This project allows users to:
- Track live cryptocurrency prices.
- View historical trends with interactive charts.
- Analyze global crypto market trends and statistics.

## Features
- **Real-Time Data:** Stay updated with live crypto data.
- **Interactive Charts:** Visualize market trends with Chart.js.
- **Responsive Design:** Built using Ant Design for an intuitive UI.
- **API Integration:** Leverages multiple APIs via RapidAPI.
- **State Management:** Efficiently managed with Redux Toolkit.

## Technologies Used
- **Frontend Framework:** React.js
- **UI Library:** Ant Design
- **State Management:** Redux Toolkit
- **HTTP Requests:** Axios
- **Charting Library:** Chart.js and React-Chartjs-2
- **Utility Libraries:** Moment.js, Millify

## Setup Instructions
### Prerequisites
Make sure you have the following installed:
- Node.js (v14 or later)
- npm (v6 or later) or Yarn

### Steps
0. Copy .env.example to .env and paste your credentials.
1. Clone the repository:
   ```bash
   git clone https://github.com/ShivaMani02/CrytoAnalyser-Project-react
   ```

2. Navigate to the project directory:
   ```bash
   cd CryptoAnalyser
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open the app in your browser at `http://localhost:3000`.

## Project Structure
```
CryptoAnalyser/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── CryptoList.jsx
│   │   ├── CryptoDetails.jsx
│   │   └── Chart.jsx
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Cryptocurrencies.jsx
│   │   ├── News.jsx
│   │   └── Details.jsx
│   ├── app/
│   │   ├── store.js
│   │   └── api.js
│   ├── assets/
│   ├── App.js
│   ├── index.js
│   └── styles.css
├── .eslintrc.js
├── package.json
└── README.md
```

## Scripts
- **Start Development Server:**
  ```bash
  npm install
  npm start
  ```

- **Build for Production:**
  ```bash
  npm run build
  ```

- **Run Tests:**
  ```bash
  npm test
  ```

## API Integration
This project uses APIs from RapidAPI for fetching cryptocurrency data. Replace placeholders in `api.js` with your RapidAPI key.

Example:
```javascript
const options = {
  method: 'GET',
  url: 'https://api.rapidapi.com/endpoint',
  headers: {
    'X-RapidAPI-Key': 'YOUR_RAPIDAPI_KEY',
    'X-RapidAPI-Host': 'api.rapidapi.com'
  }
};
```

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
**Happy Coding!** 🎉

