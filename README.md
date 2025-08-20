Bwire Aesthetic Shop
Quality Tech, Aesthetic Vibe.

Bwire Aesthetic Shop is a modern, full-featured e-commerce platform designed for selling electronics and phone accessories, primarily targeting the Kenyan market. It provides a seamless shopping experience with a clean, aesthetic user interface and a robust set of features for both customers and administrators.

✨ Features
This project is packed with features to create a complete e-commerce ecosystem:

🏠 Homepage: A beautiful landing page with a hero section, featured products, and customer testimonials.

🛍️ Shop Page: A comprehensive product listing page with advanced filtering by category, brand, and price range.

👤 Customer Accounts: Full authentication system (Login, Sign Up, Password Reset) for a personalized user experience.

🛒 Shopping Cart: A fully functional cart modal allowing users to add, remove, and update product quantities.

❤️ Wishlist: Users can save their favorite items to a personal wishlist.

📝 Blog: A section for tech tips, reviews, and articles to engage the community.

💬 Community Hub: An interactive forum where users can create posts (anonymously or not), comment, reply, and like content. It includes features like mentions, hashtags, and trending topics.

🔔 Notifications: Real-time notifications for user mentions and other interactions.

🔑 User Dashboard: A dedicated space for users to view their profile, order history, and manage their wishlist.

💳 Checkout System: A simulated checkout process with options for M-PESA and Cash on Delivery.

📱 Fully Responsive: Designed to work beautifully on all devices, from mobile phones to desktops.

🛠️ Tech Stack
The project is built with a modern, scalable, and efficient technology stack:

Frontend: HTML5, Tailwind CSS, Vanilla JavaScript

Backend & Database: Google Firebase (Firestore for database, Firebase Authentication for user management)

UI Components:

Flatpickr for the date picker in the community section.

Tone.js for notification sounds.

Fonts: Google Fonts (Poppins)

🚀 Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
You don't need any special tools to run this project. A modern web browser is all that's required to open the index.html file. For development, a code editor like VS Code is recommended.

Installation
Clone the repo:

git clone https://github.com/eugeneasande/bwireaestheticshop.git

Navigate to the project directory:

cd bwireaestheticshop

Open index.html in your browser to view the site.

Firebase Setup
This project is configured to connect to a Firebase project. To use your own Firebase backend:

Go to the Firebase Console and create a new project.

Enable Firestore Database and Firebase Authentication (with Email/Password provider).

In the index.html file, find the <script> tag near the end of the <body>.

Replace the existing firebaseConfig object with your own project's configuration keys.

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};

You will also need to set up the Firestore database with the required collections (products, testimonials, blogPosts, community_posts, users, settings, etc.) for the site to function correctly.

🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

Don't forget to give the project a star! Thanks again!

📧 Contact
Project Author: eugz_asax

Project Link: https://github.com/eugeneasande/bwireaestheticshop

This README was generated with assistance from Gemini.
