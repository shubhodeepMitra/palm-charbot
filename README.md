# Character-based Chatbot App using PALM2

## Installation
To use this chatbot project, you'll need Node.js and npm on your machine.

Clone the GitHub repository to your local machine. Navigate into the project folder.

### Frontend
Run to get all required dependencies. 
```bash
   npm install
``` 

Start the development server with 
```bash
   npm start
```  

The app will now be available at `http://localhost:3000`.

### Backend

Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
Start the development server:
   ```bash
   flask run
   ```
The API will be available at `http://localhost:5000`.

#### API Endpoints

- `/detail`: POST request to get the details of a character.
- `/chat`: POST request to send a message to the chatbot and get a response.

### Use Case
In the chatbot, first, you'll need to enter the name of the character you want it to act like. This will fetch that character's bio and example dialogues.

You can now have a conversation with the chatbot, which will try to respond in the style of the chosen character.

### Reference
https://lablab.ai/t/palm2-tutorial-building-character-based-chatbot-app-using-powerful-ai-model#dialoguecontainertsx
