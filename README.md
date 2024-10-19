# Sign Language Translator for Virtual Meetings

## PVGOE - one man army
**Participant:**
- Name: 
- Role: Developer
- Email: 

## Problem Statement
### Theme:
Enhancing accessibility in virtual meetings.

### Description:
The goal of this project is to develop a plugin for popular meeting platforms like Microsoft Teams or Zoom that translates spoken conversations into sign language in real-time. This plugin will enable participants who are deaf or hard of hearing to engage fully in conversations by seamlessly translating spoken words into sign language.

### User Interaction:
The plugin will integrate smoothly with existing meeting applications, allowing users to activate the sign language translation feature with a simple click. It will display a sign language interpreter alongside the video feed or in a designated panel.

### Real-Time Translation:
The project will implement real-time speech recognition and sign language translation, converting spoken words into text and subsequently into sign language animations or video representations. The translation will be accurate and synchronized with the conversation.

### Expected Solution:
- Seamless integration with Teams or Zoom.
- User-friendly interface to enable/disable sign language translation.
- Use of open-source speech-to-text tools for real-time transcription.
- Conversion of text into sign language using animated avatars or pre-recorded videos.
- Presentation of sign language translation in a non-intrusive manner.

### Bonus Features (Nice-to-haves):
1. **Multiple Sign Language Support**: Include various sign languages (e.g., ASL, BSL).
2. **Adaptive Learning**: Implement machine learning to improve translation accuracy based on feedback.
3. **Interactive Features**: Add functionalities such as clickable signs for definitions and the ability to pause/replay translations.

## Instructions on Running Your Project

### Prerequisites:
- Node.js and npm installed on your system.
- Access to the Zoom or Microsoft Teams API (for plugin development).

### Step-by-Step Instructions:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/jayeshpandey01/one-man-army-PVGOE.git
   cd https://github.com/jayeshpandey01/one-man-army-PVGOE.git
   
2. **Install Dependencies: Make sure you're in the project directory and run:**
   ```bash
   npm install
   
3. **Set Up API Credentials:
   
Obtain API keys for Zoom or Microsoft Teams.
Create a .env file in the root directory and add your API credentials:**
   ```bash
    ZOOM_API_KEY=your_zoom_api_key
    ZOOM_API_SECRET=your_zoom_api_secret
    TEAMS_API_KEY=your_teams_api_key
```

4. Run the Application: To start the local server, use:
   ```bash
   npm start
   
5. Testing the Plugin:
Open the web app in your browser (default: http://localhost:3000).
Start a test meeting on Zoom or Microsoft Teams and activate the sign language translation feature through the interface.

6. Accessing Speech Recognition: Ensure your microphone is enabled and the application has permission to access it.

7. Using the Sign Language Translation:
During a meeting, enable the sign language translation option.
The translated sign language should appear in the designated panel or overlay.


## References
- [Google Speech-to-Text API Documentation](https://cloud.google.com/speech-to-text/docs)
- [OpenAI's GPT API](https://beta.openai.com/docs/)
- [Sign Language Animation Resources](https://www.example.com)  <!-- Replace with actual resource link -->
- [Zoom API Documentation](https://marketplace.zoom.us/docs/api-reference/zoom-api)
- [Microsoft Teams Developer Documentation](https://docs.microsoft.com/en-us/microsoftteams/platform/)
