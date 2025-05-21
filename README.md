# 🎧 Harmony Hub – Stream Music and Socialize in Real-Time

**Harmony Hub** is a full-stack music streaming web app that blends rich playback features with real-time social interaction. Built with modern web technologies, it allows users to stream music, see who’s online, chat with friends, and explore curated albums—all from a clean and responsive interface.

Whether you're vibing solo or discovering music together, Harmony Hub makes streaming more social and engaging.

---

## Tech Stack

### Frontend
-  **React.js + Vite** – Lightning-fast and modern
-  **Tailwind CSS** – Fully responsive UI styling
-  **Zustand** – Lightweight state management
-  **ShadCN UI** – Accessible component design
-  **React Router** – Page routing and navigation

### Backend
-  **Node.js + Express.js** – REST API framework
-  **Clerk** – Google-based authentication (OAuth 2.0)
-  **Socket.IO** – Real-time chat and user activity tracking
-  **Multer** – Media file uploads (album covers, songs)
-  **MongoDB + Mongoose** – NoSQL data persistence
-  **Cloudinary** – Scalable media storage and streaming

### Deployment
-  **Frontend** – Deployed on Vercel
-  **Backend** – Deployed on Render (Node web service)

---

##  Key Features

###  Authentication & Roles
- Google Sign-In (Clerk)
- Persistent sessions
- Role-based routing: Admin vs. Regular user

###  Admin Panel
- Add/edit/delete albums and songs
- Upload album covers and audio files
- View real-time platform stats (songs, users, albums)

###  Music Streaming
- Queue-based playback system
- Responsive audio controls: skip, pause, loop, volume
- Album-specific pages with metadata
- Home feed with randomized recommendations

###  Real-Time Chat
- One-on-one live messaging
- Online/idle/offline status indicators
- Activity bar showing current listening status
- Powered by Socket.IO

---

##  Interface Preview

###  Home Page  
Users land on a dynamic home screen featuring a randomized “Recommended for You” section.

![Home Page](https://github.com/sanjay-xoxo/Harmony-Hub/assets/homepage.png)

---

###  Album Page  
Each album contains a tracklist with album art, artist info, and streamable songs.

![Album Page](https://github.com/sanjay-xoxo/Harmony-Hub/assets/album.png)

---

###  Admin Dashboard  
Admins can manage songs, albums, and view stats from an intuitive dashboard.

![Admin Dashboard](https://github.com/sanjay-xoxo/Harmony-Hub/assets/admin.png)

---

###  Chat Page  
Users can message each other in real-time with timestamped messages.

![Chat Page](https://github.com/sanjay-xoxo/Harmony-Hub/assets/chat.png)

---

###  Activity Bar  
At a glance, see who’s listening, who’s idle, and who’s offline.

![Activity Bar](https://github.com/sanjay-xoxo/Harmony-Hub/assets/activity.png)

---

##  Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/harmony-hub.git
cd harmony-hub

### 2. Configure Environment Variables
Create .env files for both client and server folders.

You'll need:

Clerk publishable key

MongoDB URI

Cloudinary cloud name, API key & secret

3. Install & Run

# Client
cd client
npm install
npm run dev

# Server
cd ../server
npm install
npm run dev

