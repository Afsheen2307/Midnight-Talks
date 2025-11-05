# Midnight-Talks
# Midnight-Talks

A web app (in building) that will connect you with your friends via chats **without storing any data**.

##  Features
- Real-time chat between users  
- No persistent data storage: designed to keep things ephemeral/private  
- Simple client + backend architecture (see folder layout below)

##  Folder Structure
/client – Front-end code
/backend – Back‐end / server code
.gitignore – Files/folders to ignore


## 🧰 Tech Stack
- Front-end: HTML, CSS, JavaScript  
- Back-end: Node.js (or whatever backend you’re using)  
- Real-time messaging via sockets (or similar)  
- No long-term data persistence (databases) – for privacy & simplicity

## 🔧 Getting Started

### Prerequisites  
- Node.js installed  
- npm or yarn for package management  
- (Optional) A local environment for front-end/front-end and backend

### Installation  
```bash
# Clone the repository
git clone https://github.com/imsks/Midnight-Talks.git
cd Midnight-Talks

# Install dependencies for backend
cd backend
npm install

# Install dependencies for client
cd ../client
npm install

### Running the app
# From backend folder
cd backend
npm start

# In another terminal: from client folder
cd ../client
npm start

Then open your browser at http://localhost:<clientPort> (e.g., http://localhost:3000) and chat away!

Usage
Once both backend and client are running:
Open the client URL in your browser
Connect with a friend (via link / room code / similar)
Start chatting in real-time
No chat logs are stored permanently — once closed, your conversation is gone

Contributing
Contributions are welcome! Here’s how you can help:
Report bugs or issues via GitHub Issues
Add new features (e.g., video chat, file sharing, emoji support)

Improve UI/UX
Write tests and improve reliability
Please fork the repo, create a branch, make your changes, and submit a pull request.

Disclaimer
This app is still under development. Use it at your own risk. While chats are not stored by design, none of this is a guarantee of privacy — please consider security and privacy implications before using in production or sharing sensitive information.

Thanks for checking out Midnight-Talks! 🎉
Feel free to reach out for feedback or help.
