# PublishHub

## Digital News Publishing and Reading Platform

**PublishHub** is a cutting-edge, responsive digital platform designed to empower independent writers and media houses to seamlessly publish and distribute news articles, while providing readers with access to a diverse and rich content library. Built with the MERN stack and enhanced with powerful AI integrations, PublishHub redefines the digital news experience.

## ✨ Features

  * **📰 Digital Publishing & Reading:** A robust platform for writers to publish and readers to consume news articles.
  * **🌐 Multi-Language Support:** Integrated Google Translate API allows users to read articles in **more than 10 different global and regional languages**, breaking down language barriers.
  * **🗣️ AI-Powered Summarization & Audio:**
      * **News Summarization:** Utilizes Hugging Face APIs to provide concise summaries of long articles, saving readers time.
      * **News-to-Audio:** Converts articles into audio, enabling users to listen to content with customizable playback speed, perfect for on-the-go consumption.
  * **🔒 Secure Authentication:** Implemented secure Google OAuth authentication with JSON Web Tokens (JWT) for a seamless and protected user experience.
  * **🔄 Optimized State Management:** Efficient state management with Redux, handling all CRUD (Create, Read, Update, Delete) operations, image uploads, and secure account deletion.
  * **🔍 Advanced Search Functionality:** Powerful search capabilities to help users quickly find relevant articles.
  * **🎨 Dynamic UI:**
      * **Light/Dark Mode:** Users can switch between light and dark themes for optimal viewing comfort.
      * **Lazy Loading:** Enhances performance by loading content only when needed.
  * **📊 Advanced User Dashboard:** A personalized dashboard for users to manage their likes, comments, and published articles efficiently.
  * **⚡ Performance Optimized Deployment:**
      * Deployed on **Render**, leveraging **Cron jobs** to significantly reduce loading time by **95%**, effectively mitigating Render’s 15-minute inactivity sleep rule.

## 🚀 Demo

  * **Demo Video:** [Link to your Demo Video on YouTube or other platform] (Please replace with your actual link)
  * **Live Website:** [Link to your Live Website on Render] (Please replace with your actual link)

## 🛠️ Technologies Used

  * **Frontend:**
      * React.js
      * Redux Toolkit (for state management)
      * React Router
      * Tailwind CSS (or other styling library if used)
      * Axios
  * **Backend:**
      * Node.js
      * Express.js
      * MongoDB (with Mongoose ORM)
      * Firebase (for image storage or other services)
      * jsonwebtoken (JWT)
      * bcryptjs (for password hashing)
  * **APIs & Integrations:**
      * Google Translate API
      * Hugging Face APIs (for summarization and text-to-speech)
      * Google OAuth
  * **Deployment:**
      * Render
      * Cron jobs

## 📦 Installation & Setup

To get a local copy up and running, follow these simple steps:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Garima-Khandelwal-1/PublishHub.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd PublishHub
    ```

3.  **Install backend dependencies:**

    ```bash
    cd backend # or wherever your backend directory is located
    npm install
    ```

4.  **Install frontend dependencies:**

    ```bash
    cd ../frontend # or wherever your frontend directory is located
    npm install
    ```

5.  **Set up environment variables:**
    Create a `.env` file in your `backend` directory and add the following (replace with your actual values):

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    GOOGLE_CLIENT_ID=your_google_oauth_client_id
    GOOGLE_CLIENT_SECRET=your_google_oauth_client_secret
    FIREBASE_API_KEY=your_firebase_api_key
    HUGGING_FACE_API_KEY=your_hugging_face_api_key
    # Add any other environment variables
    ```

    Similarly, create a `.env` file in your `frontend` directory for any client-side environment variables.

6.  **Run the backend server:**

    ```bash
    cd backend
    npm start
    ```

7.  **Run the frontend application:**

    ```bash
    cd ../frontend
    npm start
    ```

The application should now be running on `http://localhost:3000` (frontend) and `http://localhost:5000` (backend) or your configured ports.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. Don't forget to give the project a star\! Thanks\!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License
No specific license applied

## 📞 Contact

Garima Khandelwal - [garimakhandelwal077@gmail.com] - [[Your LinkedIn Profile URL](https://www.linkedin.com/in/garima-khandelwal-4b3967269/)]

Project Link: [https://github.com/Garima-Khandelwal-1/PublishHub](https://www.google.com/search?q=https://github.com/Garima-Khandelwal-1/PublishHub)

-----
