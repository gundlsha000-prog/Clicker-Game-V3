📌 PROJECT DESCRIPTION

A browser-based incremental clicker game built using HTML, CSS, JavaScript, and Firebase.
The application supports real-time multiplayer synchronization, allowing multiple users to interact with shared data such as scores, upgrades, and leaderboard rankings. MADE USING VS CODE WITH FLASK APP INSTALLATION. You can play my game here: https://clicker-game-v3.onrender.com

The system uses Firebase Authentication and Firestore to manage user sessions and persist game state across devices.

⚙️ CORE FUNCTIONALITY
Click-based scoring system with upgrade scaling
Auto-increment (idle progression) system
Real-time global leaderboard (Firestore sync)
Live chat system between connected users
Persistent player data storage in cloud database
Username-based player identification

🧱 ARCHITECTURE
Frontend: HTML5 + CSS3 + Vanilla JavaScript (ES Modules)
Backend (BaaS): Firebase
Authentication (Anonymous / User-based)
Firestore (Real-time database)

🔄 DATA FLOW
User interacts with UI (click / upgrade / chat)
JavaScript updates local game state
Changes are pushed to Firestore
Firestore broadcasts updates to all connected clients
UI re-renders in real-time

📌 NOTES
app.py is not required for production use
Game logic is fully client-side
Firebase handles synchronization and persistence
