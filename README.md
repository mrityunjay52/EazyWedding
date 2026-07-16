
Here is a fully formatted `README.md` file based on the details you provided. I’ve structured it with clear headings, lists, and code blocks so it is easy to read and ready to be dropped straight into your GitHub repository.

---

# EazyWed: Where Elegance Meets Joy

EazyWed is a comprehensive wedding planning platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It simplifies the wedding planning process by providing tools for vendor booking, budget management, digital invitations, and personalized recommendations, making it easier for users to plan their special day with elegance and joy.

---

## 🌟 Features

### 1. Vendor Booking and Management

* **Vendor Search and Filtering:** Browse vendors by category, location, price, and ratings using intuitive search and filter tools.
* **Vendor Comparison:** Compare vendor services, pricing, and reviews side-by-side to make informed decisions.
* **Booking System:** Securely book vendors directly through the platform with integrated payment options.
* **Vendor Communication:** Communicate with vendors via in-app messaging for seamless coordination.

### 2. Personalized Recommendations

* **AI-Driven Suggestions:** Receive vendor recommendations tailored to user preferences, budget, and location using a recommendation engine.
* **Preference-Based Matching:** Input wedding style, theme, and requirements to get curated vendor lists.
* **Dynamic Updates:** Recommendations adapt as users update their preferences or budget.

### 3. Real-Time Budget Tracking

* **Budget Planner:** Set and manage a wedding budget with categorized expense tracking (e.g., venue, catering, decor).
* **Real-Time Updates:** Automatically update the budget as bookings are made or expenses are added.
* **Cost Estimation:** View estimated costs for services based on vendor quotes and user selections.
* **Alerts and Insights:** Receive alerts for overspending and insights for cost-saving opportunities.

### 4. Customizable Digital Invitations

* **Template Library:** Choose from a variety of customizable wedding invitation templates.
* **Card Editor:** Use a drag-and-drop editor to personalize text, images, and design elements.
* **Digital Delivery:** Send invitations via email or WhatsApp with RSVP tracking.
* **Preview and Share:** Preview designs in real-time and share with guests seamlessly.

### 5. User and Vendor Profiles

* **User Profiles:** Manage wedding plans, track bookings, and save favorite vendors in a personalized dashboard.
* **Vendor Profiles:** Showcase services, portfolios, pricing, and availability for potential clients.
* **Profile Customization:** Update profile details, including photos, descriptions, and contact information.
* **Verification System:** Ensure trust with verified vendor profiles and user accounts.

### 6. Feedback and Review System

* **Vendor Reviews:** Rate and write reviews for vendors based on service quality and experience.
* **Review Moderation:** Admin-moderated reviews to ensure authenticity and relevance.
* **Rating System:** View aggregated vendor ratings to aid decision-making.
* **Feedback Loop:** Vendors can respond to reviews to address concerns or thank clients.

### 7. AI-Customized Chatbot Assistance

* **24/7 Support:** Access an AI-powered chatbot for instant assistance with platform navigation and queries.
* **Personalized Guidance:** Get tailored advice on vendor selection, budget planning, and invitation design.
* **FAQ Integration:** Quickly resolve common questions with pre-programmed responses.
* **Vendor Inquiry Support:** Facilitate communication by drafting messages or queries to vendors.

---

## 🛠️ Technology Stack

* **MongoDB:** NoSQL database for storing application data.
* **Express.js:** Web framework for building the backend API.
* **React.js:** JavaScript library for building the user interface.
* **Node.js:** JavaScript runtime for the backend server.

---

## ⚙️ Installation and Setup

### Prerequisites

* **Node.js:** Version 14.x or higher recommended.
* **MongoDB:** Locally installed or a cloud instance like MongoDB Atlas.
* **Git:** For cloning the repository.

### Cloning the Repository

```bash
git clone https://github.com/mrityunjay52/EazyWedding.git
cd EazyWed

```

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend

```


2. Install backend dependencies:
```bash
npm install

```


3. Set up environment variables:
Create a `.env` file in the `backend` directory and add the following variables (replace with your own values):
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
TWILIO_ACCOUNT_SID=your_twilio_account_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number

```


4. Start the backend server:
```bash
npm start

```


*The backend server will run on `http://localhost:5000` (or the port specified in `.env`).*

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd ../eazywed

```


2. Install frontend dependencies:
```bash
npm install

```


3. Set up environment variables:
Create a `.env` file in the `eazywed` directory and add the following variable:
```env
VITE_API_URL=http://localhost:5000

```


4. Start the frontend development server:
```bash
npm run dev

```


*The frontend will run on `http://localhost:5173` (or the port assigned by Vite).*

---

## 🚀 Running Both Servers

To run both the backend and frontend servers simultaneously, you have two options:

**Option 1: Two Terminals**

1. In the first terminal, navigate to `EazyWed/backend` and run: `npm start`
2. In the second terminal, navigate to `EazyWed/eazywed` and run: `npm run dev`

**Option 2: Using Concurrently**

1. Install `concurrently` globally:
```bash
npm install -g concurrently

```


2. From the root `EazyWed` directory, run:
```bash
concurrently "cd backend && npm start" "cd eazywed && npm run dev"

```



---

## 💻 Importing the Project into Your IDE

1. Open your preferred IDE (e.g., VS Code).
2. Use the "Open Folder" option and select the root `EazyWed` directory.
3. Ensure you have the necessary extensions installed (e.g., ESLint, Prettier for JavaScript/React development) for the best developer experience.

---

## 📱 Usage

* Open your browser and navigate to `http://localhost:5173` to access the EazyWed frontend.
* Register as a user or vendor to explore features like booking vendors, creating digital invitations, or managing budgets.
* Admin features are accessible via the admin dashboard (requires admin credentials).
* Use the AI-customized chatbot (available on the platform) for assistance with navigation, vendor selection, or general queries.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve EazyWed, please feel free to fork the repository, create a new branch, and submit a pull request. Ensure your code aligns with the existing style and that any new features are properly documented.
