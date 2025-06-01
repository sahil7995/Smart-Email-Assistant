# Smart Email Assistant - Google Extension

An intelligent email assistant implemented as a Google Chrome extension that leverages AI to automate email composition and replies directly within Gmail.

## Synopsis

This project introduces an intelligent email assistant integrated as a Google Chrome extension that leverages AI to automate email composition and replies. The extension seamlessly embeds within the Gmail interface, providing users with a convenient **Generate** button adjacent to the standard **Send** option.

Users can input the desired email content and specify the tone or style for the reply, enabling the generation of contextually appropriate and professionally styled email responses. The solution is built using a modern technology stack, including **Java**, **Spring Boot**, **React**, **JavaScript**, **HTML**, and **CSS**, ensuring scalability and responsiveness.

The architecture allows easy configuration of the AI API key, facilitating integration with various AI providers for natural language generation capabilities. This innovation significantly enhances productivity by simplifying email management and minimizing manual effort.

## Features

- AI-powered email content generation with tone customization
- Real-time integration with Gmail’s user interface
- Simple and intuitive user experience
- Built with scalable and modern web technologies

## Technologies Used

- Java and Spring Boot (backend API)
- React, JavaScript, HTML, CSS (frontend UI and extension)
- Google Chrome Extension APIs
- AI API for natural language generation (configurable via API key)

## Getting Started

### Prerequisites

- Java 11+ and Maven or Gradle
- Node.js and npm or yarn
- Google Chrome browser
- AI API key (e.g., OpenAI API key)

### Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/sahil7995/Smart-Email-Assistant.git
   cd Smart-Email-Assistant
   cd email-writer-back_end
   
2. Configure your AI API key in the application.properties file.
   
3. Build and run the backend Spring Boot service:

   ```bash
   ./mvnw spring-boot:run

4. Navigate to the frontend directory, install dependencies, and start the React app:

   ```bash
   cd Smart-Email-Assistant
   cd email-writer-front_end
   npm install
   npm start

5. Load the Chrome extension:

   Open Chrome and go to chrome://extensions/
   Enable Developer mode
   Click Load unpacked and select the extension folder

6. Open Gmail, compose a new email or reply to an existing one, and use the Generate button added by the extension to automatically create email content.

## Future Improvements

-Support for scheduling and sending emails automatically

-Multi-language support for broader accessibility

-Enhanced AI tone and voice recognition

-UI/UX improvements for better usability

## Contributing
Contributions are welcome! Please submit issues or pull requests to help improve the project.

## License
This project is licensed under the MIT License.

Created with ❤️ by Sahil Bhandari

