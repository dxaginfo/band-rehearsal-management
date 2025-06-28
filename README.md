# Band Rehearsal Management

An automated web app for band rehearsal scheduling, attendance tracking, reminders, and conflict management. 

## Features
- User authentication (JWT/OAuth)
- Google/Outlook calendar sync
- Create/edit rehearsal events
- Member invitations and attendance
- Availability polling and conflict resolution
- Automated reminders (email/SMS)
- Mobile-responsive (React+Material UI)
- PostgreSQL-backed
- Dockerized deployment

## Setup Instructions
1. Clone the repo
2. `cd band-rehearsal-management`
3. `docker-compose up --build`
4. Access the app at http://localhost:3000

## Environment Variables
- Add keys for PostgreSQL, Google OAuth, SendGrid/Twilio

## Deployment
See docker-compose.yml and Dockerfile. 

## Roadmap
- Spotify/Bandcamp integration
- Admin analytics dashboard
