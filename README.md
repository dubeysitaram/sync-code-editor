# Sync Code Editor

Sync Code Editor is a real-time collaborative code editing platform, where multiple users can join a room and edit code together. It supports features like live code syncing, user avatars, and a simple yet powerful code editor powered by CodeMirror.

## Features

- **Real-time Code Syncing**: All users connected to the same room can see and edit the code in real time.
- **Multiple Users**: Users can join rooms with unique Room IDs and work together.
- **CodeMirror Editor**: A feature-rich JavaScript editor with auto-closing tags, brackets, and more.
- **User Avatars**: Display avatars based on the username.
- **Notifications**: Users receive notifications when others join or leave the room.
- **Share Feature**: Users can share their code snippets with others via a unique shareable link.

## Technologies Used

- **Frontend**: React.js, React Router, React Hot Toast, CodeMirror, Socket.IO
- **Backend**: Express.js, Socket.IO
- **Database**: Socket.IO handles real-time code synchronization

## Prerequisites

- Node.js - v20.12.1
- npm  - 10.5.1

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/dubeysitaram/sync-code-editor.git
   ```

2. Install dependencies:

     ```npm install```

   OR

    ```yarn install```

### Running the Application

1. Run Server:
   
     ```cd api```
   
     ```node server.js```
   
3. Run Frontend:

    ```npm start```

## Screenshots




