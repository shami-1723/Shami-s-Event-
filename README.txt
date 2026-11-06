SHAMIS EVENT MANAGER
College Event Management System (Express + MySQL)

SETUP
1. Install Node.js and MySQL.
2. Open this project folder in a terminal.
3. Install dependencies:
   npm install
4. Create the database and events table:
   mysql -u root -p < schema.sql
5. Set your MySQL credentials before starting the server.

PowerShell (current terminal session):
   $env:DB_HOST="localhost"
   $env:DB_USER="root"
   $env:DB_PASSWORD="YOUR_MYSQL_PASSWORD"
   $env:DB_NAME="shamis_event_manager"

6. Start the application:
   npm start
7. Open http://localhost:3000 in your browser.

FEATURES
- View all events
- Search an event by Event ID
- Add a new event
- Update event details
- Delete an event

The app uses MySQL for storage. Images load from Unsplash when internet is
available; gradient backgrounds are used as a fallback.
