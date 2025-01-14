# Notes App Project

## **Introduction**
This project is a fully responsive Notes App with AI-powered features such as sentiment analysis and note summarization. It allows users to create, view, edit, and delete notes while leveraging AI for additional insights. This guide will walk you through setting up the project on a Windows machine.

---

## **Prerequisites**

Before you begin, ensure you have the following installed on your system:

1. **Node.js**: Download and install Node.js from [https://nodejs.org/](https://nodejs.org/).
   - During installation, ensure the "Add to PATH" option is checked.

2. **Git**: Download and install Git from [https://git-scm.com/](https://git-scm.com/).

3. **IDE/Text Editor**: Use a code editor like [VS Code](https://code.visualstudio.com/).

4. **API Keys**:
   - Hugging Face API Key: Sign up at [Hugging Face](https://huggingface.co/) and get your API key.

---

## **Installation Steps**

### **Step 1: Clone the Repository**

1. Copy the code folder you received onto your computer.
2. Open the command prompt (CMD) and navigate to the folder using `cd path_to_folder`.

### **Step 2: Install Dependencies**

#### Backend Setup

1. Navigate to the backend folder:
   ```
   cd backend
   ```

2. Install the required packages:
   ```
   npm install
   ```

#### Frontend Setup

1. Navigate to the frontend folder:
   ```
   cd ..\frontend
   ```

2. Install the required packages:
   ```
   npm install
   ```

---

## **Environment Variables**

You need to configure the environment variables for the backend.

1. Create a `.env` file in the `backend` folder.
2. Add the following variables:
   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   HUGGINGFACE_API_KEY=your_huggingface_api_key
   ```
   - Replace `your_mongodb_connection_string` with your MongoDB URI.
   - Replace `your_huggingface_api_key` with the API key from Hugging Face.

---

## **Running the Project**

### **Backend**

1. Open a terminal and navigate to the backend folder:
   ```
   cd backend
   ```

2. Start the backend server:
   ```
   npm start
   ```

   The backend will run on [http://localhost:5000](http://localhost:5000).

### **Frontend**

1. Open a new terminal and navigate to the frontend folder:
   ```
   cd frontend
   ```

2. Start the React development server:
   ```
   npm start
   ```

   The frontend will run on [http://localhost:3000](http://localhost:3000).

---

## **Key Features**

1. **Authentication**: Secure login and registration for users.
2. **Notes Management**: Create, edit, view, and delete notes.
3. **AI Sentiment Analysis**: Analyze the tone of the notes.
4. **AI Summarization**: Summarize notes into concise 2-3 line descriptions.
5. **Responsive Design**: Fully adaptable for all devices.

---

## **Testing the Application**

1. Open [http://localhost:3000](http://localhost:3000) in your browser.
2. Register as a new user.
3. Log in and start creating notes.
4. Check the AI-powered features such as summarization and sentiment analysis.

---

## **FAQs**

### **1. How to Get an API Key from Hugging Face?**
- Sign up at [https://huggingface.co/](https://huggingface.co/).
- Go to your profile settings and generate an API key.
- Copy the key and update it in the `.env` file under `HUGGINGFACE_API_KEY`.

### **2. Common Errors**
- **Error: Command not recognized**: Ensure Node.js is installed and added to PATH.
- **Cannot connect to MongoDB**: Verify your MongoDB URI in `.env`.
- **API errors**: Check if your Hugging Face API key is valid.

---

## **Final Notes**

Share this guide with any team member to help them get started quickly. If you encounter issues, feel free to ask for assistance!

