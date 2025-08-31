# MailMate – AI-Powered Email Reply Assistant

MailMate is a full-stack application that leverages AI (Gemini API) to automatically generate context-aware email replies. The frontend is built with React.js and Material UI, while the backend uses Java Spring Boot. This project streamlines email communication by providing intelligent, tone-adjustable responses.

## Features

- **AI-Powered Replies:** Generates email responses using Gemini API.
- **Tone Selection:** Choose between professional, casual, or friendly tones.
- **User-Friendly UI:** Clean interface built with React and Material UI.
- **Copy to Clipboard:** Easily copy generated replies for use.
- **Error Handling:** Displays helpful error messages for failed requests.

## Tech Stack

- **Frontend:** React.js, Material UI, Axios
- **Backend:** Java Spring Boot, Maven
- **AI Integration:** Gemini API

## Getting Started

### Prerequisites

- Node.js & npm
- Java & Maven
- Gemini API Key

### Frontend Setup

1. Navigate to the frontend directory:
   ```
   cd mailMate-frontend
   ```
2. Install dependencies:
   ```
   npm install
   ```
3. Start the development server:
   ```
   npm start
   ```

### Backend Setup

1. Navigate to the backend directory:
   ```
   cd mailMate-backend
   ```
2. Build and run the Spring Boot application:
   ```
   mvn spring-boot:run
   ```
3. Ensure your Gemini API key is configured in the backend.

### Usage

- Enter the original email content.
- Select the desired reply tone.
- Click "Generate Reply" to receive an AI-generated response.
- Copy the reply to your clipboard for easy use.

## Project Structure

```
mailMate-AI/
├── mailMate-frontend/   # React.js frontend
└── mailMate-backend/    # Spring Boot backend
```

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements.

## License

This project is licensed under the MIT License.

## Author

Omkar Karhale
