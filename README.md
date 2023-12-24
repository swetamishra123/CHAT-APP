
# Chat Application using Chat Engine API

Welcome to the Chat Application! This application allows users to engage in real-time chat using the Chat Engine API.

## Demo
Check out the live demo [here](https://chat-64dmh7q2o-sweta-mishras-projects.vercel.app/)

## Features
- Real-time messaging
- Multiple users support
- Attach images to messages

## Getting Started

### Prerequisites
- Node.js installed
- React development environment

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/swetamishra123/CHAT-APP.git
   ```

2. Change to the project directory:
   ```bash
   cd CHAT-APP
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

### Set up Chat Engine API

1. Create an account on [Chat Engine](https://chatengine.io/).
2. Create a new project to obtain the Project ID.
3. Get your access keys from the Chat Engine dashboard.

### Configuration

In the project, open `MessageForm.js` and `Modal.js` files.

```javascript
// MessageForm.js
const projectID = 'YOUR_CHAT_ENGINE_PROJECT_ID';
```

```javascript
// Modal.js
const projectID = 'YOUR_CHAT_ENGINE_PROJECT_ID';
```

Replace `'YOUR_CHAT_ENGINE_PROJECT_ID'` with your actual Chat Engine Project ID.

### Run the Application

```bash
npm start
```

Visit `http://localhost:3000` in your browser to view the application.

## Usage

- Upon visiting the application, you will be prompted to log in with your Chat Engine credentials.
- Start chatting with others in real-time!

## Contributing

Feel free to contribute to the development of this project. Fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

```

Make sure to replace `'YOUR_CHAT_ENGINE_PROJECT_ID'` with your actual Chat Engine Project ID.


