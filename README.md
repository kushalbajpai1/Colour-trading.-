// Ready-to-Deploy Zip Package Instructions for Colour Trading Website

/*
This package contains both frontend and backend folders fully configured to deploy immediately.

Structure:

colour-trading-website/
├── backend/
│   ├── server.js
│   ├── package.json
│   ├── routes/
│   │    ├── auth.js
│   │    ├── trade.js
│   │    ├── wallet.js
│   ├── controllers/
│   │    ├── authController.js
│   │    ├── tradeController.js
│   │    ├── walletController.js
│   ├── models/
│   │    ├── User.js
│   │    ├── Colour.js
│   │    ├── Transaction.js
│   ├── utils/
│   │    ├── socket.js
│   │    ├── payment.js
│   │    ├── seedColours.js
│   ├── config/
│   │    ├── db.js
│   │    ├── socket.js
│   ├── .env.example

├── frontend/
│   ├── package.json
│   ├── public/
│   ├── src/
│   │    ├── App.js
│   │    ├── index.js
│   │    ├── components/
│   │    │    ├── Login.js
│   │    │    ├── Signup.js
│   │    │    ├── Dashboard.js
│   │    │    ├── Wallet.js
│   │    │    ├── TradePanel.js
│   │    │    ├── AdminPanel.js
│   │    ├── services/
│   │    │    ├── api.js
│   │    │    ├── socket.js
│   │    ├── utils/
│   │    │    ├── auth.js
│   │    ├── styles/
│   │    │    ├── tailwind.css
│   ├── .env.example

├── README.md  <- Full deployment instructions

Steps to Deploy:

1. Extract zip and push backend/frontend folders to separate GitHub repos.
2. Set up MongoDB Atlas and copy MONGO_URI.
3. Set up Stripe and Razorpay keys.
4. Deploy backend on Railway or Render, set env variables from backend/.env.example, run seedColours.js.
5. Deploy frontend on Vercel, set REACT_APP_API_URL to deployed backend URL.
6. Open frontend URL for the live working website.
   */
