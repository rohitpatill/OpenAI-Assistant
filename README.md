# OpenAI Assistant

OpenAI Assistant is a simple web-based chatbot application built using React-Vite, Node.js and Express.js.
It utilizes the OpenAI API to generate responses based on user prompts.

## Features

- Users can interact with the chatbot by entering prompts.
- Responses are generated by the OpenAI API and displayed in real-time.
- Basic styling provided by CSS.

## Technologies Used

- React-Vite
- Node.js
- Express.js
- OpenAI API

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your_username/OpenAI-Assistant.git
```

2. Navigate to the project directory:

```bash
cd OpenAIAssistant
```

3. Install dependencies:

```bash
cd client
npm install

cd ../server
npm install
```

4. Set up environment variables:

   - Create a `.env` file in the `server` directory.
   - Add your OpenAI API key to the `.env` file: `OPENAI_API_KEY=your_api_key_here`.

## Usage

1. Start the client:

```bash
cd ../client
npm run dev
```

2. Start the server:

```bash
cd ../server
npm start
```

3.Open your browser and navigate to http://localhost:5173 to use the chatbot.

## Configuration

- Replace `your_api_key_here` in the `.env` file with your actual OpenAI API key.

