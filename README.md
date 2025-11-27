# Online Music Streaming System

Work In Progress!

🎵 MusicStram: Online Music Streaming Platform!

VibeHub is a scalable, user-centric online music streaming system built using the Java Web Stack (J2EE). It connects Listeners, Artists, and Admins in a seamless ecosystem, allowing users to stream music,
create playlists, and follow artists while Admins maintain platform integrity.
🚀 Key Features
🛡️ Admin (System Manager)
* User Management: Input user details to create, update, or delete accounts and roles.
* Content Moderation: Review and Approve/Reject music content submitted by artists.
* System Settings: Configure global platform settings and view engagement analytics.
* Dashboard: Includes graphical representations of user activity and content status tables.

🎤 Artist (Content Creator)
* Upload Music: Submit tracks with metadata (Title, Album, Genre) for admin approval.
* Performance Tracking: View analytics on streams and likes via dynamic reports.
* Fan Interaction: Receive and respond to fan feedback and messages.
* Dashboard: Features upload history logs, performance charts, and interaction panels.

🎧 Listener (End User)
* Stream Music: seamless playback with genre-based filtering.
* Playlist Management: Create, edit, and manage personalized playlists.
* Social: Follow favorite artists to stay updated on new releases.
* Dashboard: Shows listening history, created playlists, and profile settings.

🏗️ System Architecture & Tech Stack
The application follows the MVC (Model-View-Controller) architecture:
* Frontend: HTML5, CSS3, JavaScript (Responsive Dashboard UI).
* Backend: Java Servlets (Logic), JSP (View), JDBC (Database Connection).
* Database: MySQL (Relational Schema for Users, Songs, Playlists).
* Server: Apache Tomcat 9.0+.

📊 Database Design
* Users Table: Stores credentials, roles, and profile data.
* Songs Table: Stores metadata, file paths, and approval status.
* Playlists Table: Maps relationships between users and songs.
* Interactions Table: Stores likes, follows, and feedback.

🔮 Future Roadmap
* Implementation of AI-based Song Recommendations.
* Mobile Application integration.
* Live listening parties and social sharing.

