```markdown
# Next-AI: Web-Based Q&A AI Agent for PDF Document Queries

## Project Introduction

**Next-AI** is a full-stack web application designed to empower users to interact seamlessly with PDF documents. By uploading a PDF, users can ask both text-based and voice-based questions about its content and receive intelligent, real-time answers. The system leverages advanced natural language processing through the OpenAI API, providing an interactive and speech-enabled experience for effortless document querying.

- **Frontend:** Built with React
- **Backend:** Powered by Node.js and Express
- **AI Integration:** Utilizes OpenAI API for natural language processing

## Demo Video

[![Demo Video](https://img.youtube.com/vi/15BIf1xnQI4/0.jpg)](https://drive.google.com/file/d/15BIf1xnQI4hd_g-rZrbCd4aG0ANzY6-A/view?usp=drive_link)

*Click the image above to watch the demo video.*

## Features

- **PDF Upload:** Easily upload your PDF documents for querying.
- **Text-Based Queries:** Ask questions in text form and receive accurate answers.
- **Voice-Based Queries:** Use speech to ask questions and hear spoken responses.
- **Real-Time Responses:** Get intelligent answers instantly.
- **Interactive Experience:** Seamless integration of text and voice interactions for a user-friendly experience.

## Installation

Follow the steps below to set up and run Next-AI on your local machine:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/next-ai.git
   cd next-ai
   ```

2. **Install Dependencies**

   - **Frontend:**

     ```bash
     cd frontend
     npm install
     ```

   - **Backend:**

     ```bash
     cd ../backend
     npm install
     ```

3. **Configure Environment Variables**

   - Navigate to the `backend` directory.
   - Create a `.env` file if it doesn't exist.
   - Add your OpenAI API key:

     ```env
     OPENAI_API_KEY=your_openai_api_key_here
     ```

4. **Run the Application**

   From the root directory of the project, run:

   ```bash
   npm run dev
   ```

   This command will start both the frontend and backend servers concurrently.

5. **Access the Application**

   Open your browser and navigate to `http://localhost:3000` to start using Next-AI.

## Usage

1. **Upload a PDF:**
   - Click on the upload button and select the PDF document you want to query.

2. **Ask Questions:**
   - **Text-Based:** Type your question in the input field and submit.
   - **Voice-Based:** Click the microphone icon and speak your question.

3. **Receive Answers:**
   - View the text response directly on the screen.
   - If using voice input, listen to the spoken response.

## Technologies Used

- **Frontend:** React, HTML5, CSS3
- **Backend:** Node.js, Express.js
- **AI Services:** OpenAI API
- **Other Tools:** Git, npm

## Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the Repository**
2. **Create a Feature Branch**

   ```bash
   git checkout -b feature/YourFeature
   ```

3. **Commit Your Changes**

   ```bash
   git commit -m "Add your message"
   ```

4. **Push to the Branch**

   ```bash
   git push origin feature/YourFeature
   ```

5. **Open a Pull Request**

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or feedback, please contact [your-email@example.com](mailto:your-email@example.com).

```
