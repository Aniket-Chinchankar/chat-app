# ChitChat - Real-Time Chat Application  

## Overview  

ChitChat is a real-time chat application that allows users to join, send messages, and interact with others in a seamless and dynamic environment. Users are assigned random usernames and avatars upon joining and can update their usernames during the chat.  

## Features  

- **Real-Time Messaging**: Communicate with users instantly.  
- **Dynamic Usernames**: Auto-generated usernames for new users, with an option to update them.  
- **Avatars**: Each user is assigned a unique avatar based on their username.  
- **Join/Leave Notifications**: Get notified when users join or leave the chat.  

## Tech Stack  

- **Backend**: Flask (Python) with Flask-SocketIO for real-time communication.  
- **Frontend**: HTML, CSS, and JavaScript (template rendering via Flask).  
- **Socket.IO**: For bidirectional communication between the client and server.  

## Installation  

### Prerequisites  

Ensure you have the following installed:  
- Python 3.x  
- pip (Python package manager)  

### Steps  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/Aniket-Chinchankar/chat-app.git 
   cd chat-app  
   ```  

2. Install the required dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. Run the application:  
   ```bash  
   python app.py  
   ```  

4. Open your browser and navigate to:  
   ```  
   http://localhost:5000  
   ```  

## Usage  

1. Open the application in your browser.  
2. A random username and avatar will be assigned to you upon connecting.  
3. Send messages in the chat box to interact with other users in real time.  
4. Change your username using the username update feature.  
5. See notifications when users join or leave the chat.  

## File Structure  

```
chitchat/  
├── templates/  
│   └── index.html   # Frontend HTML file  
├── app.py           # Main application file  
├── requirements.txt # Project dependencies  
```  

## Dependencies  

- Flask  
- Flask-SocketIO  

## License  

------------------------------------------------------------  

## Contribution  

Feel free to contribute by forking the repository, creating a new branch, and submitting a pull request.  

---

Let me know if you need further updates!
