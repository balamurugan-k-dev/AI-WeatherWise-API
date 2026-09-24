# AI WeatherWise

AI WeatherWise is a RESTful backend application that provides real-time weather information and uses Google Gemini AI to generate intelligent weather summaries and personalized recommendations.

👥 Team Details

Team ID: SWTID-2026-6318
Team Size: 5
Team Leader: BALAMURUGAN K

Team Members:

- BHARATH B
- VANITHA E
- HARIPRASATH M
- ABISHEK RAJ K

✨ Features

- 🔐 User Registration & Login
- 🔑 JWT-based Authentication
- 📍 Manage Favorite Locations
- 🌤️ Fetch Real-time Weather Information
- 🤖 AI-powered Weather Summaries
- 💡 Personalized Weather Recommendations
- 🗄️ MongoDB Data Storage
- 🛡️ Secure Password Hashing & Request Handling

🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- Google Gemini AI
- JWT
- bcryptjs
- Postman / Thunder Client

🏗️ Architecture

The backend follows the MVC (Model-View-Controller) architecture.

Client
  ↓
Express.js API
  ↓
Controllers
  ↓
Services / Models
  ↓
MongoDB
  ↓
Gemini AI

🚀 Setup & Installation

1. Clone the Repository

git clone <repository-url>
cd AI-WeatherWise

2. Install Dependencies

npm install

3. Configure Environment Variables

Create a ".env" file:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key

«⚠️ Do not upload your actual API keys or database credentials to GitHub.»

4. Run the Project

npm start

The backend will start and connect to MongoDB.

🧪 API Testing

APIs can be tested using Thunder Client.

Main APIs include:

- Register
- Login
- Weather
- Recommendation

🎯 Project Objective

The main objective of AI WeatherWise is to combine real-time weather data with AI-generated insights, helping users understand weather conditions through simple summaries and personalized recommendations.

👨‍💻 Team

SWTID-2026-6318

- BALAMURUGAN K — Team Leader
- BHARATH B — Team Member
- VANITHA E — Team Member
- HARIPRASATH M — Team Member
- ABISHEK RAJ K — Team Member
