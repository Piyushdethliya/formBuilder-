# formBuilder-
README for Form Builder Application


---

Form Builder Application

A mobile-based form builder application created using React Native, Node.js, MongoDB, Express, and Tailwind CSS. This application allows users to create, edit, and fill forms with support for different question types: Text, Grid, and CheckBox. It also includes functionality for form preview and response saving in the backend.


---

Features

1. Form Editor UI

Users can add various types of questions: Text, Grid, and CheckBox.

Add an option to attach images to questions.

Add a header image for the form.

Responsive and user-friendly interface.



2. Form Preview/Fill

Preview the form layout before submission.

Fill out the forms and save responses to the backend.



3. Data Storage

Stores all form data, including questions and responses, in a MongoDB database.





---

Tech Stack

Frontend: React Native, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB



---

Folder Structure

form-builder/
│
├── backend/
│   ├── config/
│   │   └── db.js             # MongoDB connection setup
│   ├── controllers/
│   │   ├── formController.js # Controller for form operations
│   │   └── responseController.js # Controller for saving responses
│   ├── models/
│   │   ├── formModel.js      # MongoDB schema for forms
│   │   └── responseModel.js  # MongoDB schema for responses
│   ├── routes/
│   │   ├── formRoutes.js     # Routes for form-related APIs
│   │   └── responseRoutes.js # Routes for response-related APIs
│   ├── server.js             # Express server setup
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── FormEditor.js # Form editor component
│   │   │   ├── FormPreview.js # Form preview component
│   │   │   └── QuestionTypes/ # Components for various question types
│   │   ├── screens/
│   │   │   ├── HomeScreen.js # Home screen UI
│   │   │   └── FillFormScreen.js # Form filling screen
│   │   ├── App.js            # Main entry point for React Native
│   │   └── styles/           # Tailwind CSS configurations
│
├── README.md                 # Project documentation
└── package.json              # Project dependencies


---

How to Run

1. Prerequisites

Node.js (v14+)

MongoDB

React Native CLI

Expo CLI (optional)


2. Clone the Repository

git clone <repository-url>
cd form-builder

3. Backend Setup

cd backend
npm install
node server.js

4. Frontend Setup

cd frontend
npm install
npx react-native run-android
# or
npx react-native run-ios

5. Run the Application

Open the app in an Android or iOS emulator.



---

API Endpoints

Form APIs

POST /api/forms: Create a new form.

GET /api/forms: Get all forms.

GET /api/forms/:id: Get a single form by ID.

PUT /api/forms/:id: Update a form.

DELETE /api/forms/:id: Delete a form.


Response APIs

POST /api/responses: Submit form responses.

GET /api/responses: Get all responses.



---

Demo

Include screenshots or video links showcasing the application's functionality.


---

Contributors

Piyush Thakur (Full Stack Developer)



---

License

This project is licensed under the MIT License.


---

Let me know if you'd like to add more details or specific customizations!
