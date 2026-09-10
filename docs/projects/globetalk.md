# GlobeTalk

## Story behind the project

This was my final-year project, inspired by the traditional idea of having a pen pal. The goal was to digitize that social experience by creating a virtual pen pal system that connects random users with one another.

The project aimed to recreate the feeling of building a real connection through written communication, while making the experience more accessible in a modern digital environment.

## Anonymous Global Pen-Pal Platform

GlobeTalk is an anonymous pen-pal platform designed to help people make cross-cultural connections through asynchronous letter exchanges.

Instead of conventional real-time social messaging, users can be matched with people around the world and exchange letters that are delivered after a configurable delay.

### Technology

- **Frontend:** Next.js, React, Tailwind CSS
- **Backend:** Express / application API functionality
- **Authentication:** Firebase Auth
- **Database:** Firestore
- **Testing:** Jest, Testing Library
- **Deployment:** Netlify

### Key functionality

- Anonymous user profiles
- Global matchmaking
- Language and timezone preferences
- Asynchronous letter delivery
- Threaded inbox and composition
- Reporting and moderation
- Blocking and safety controls
- Account deletion
- Cultural profile information

### Data and privacy

The application was designed around anonymity. Public-facing profiles use anonymous identifiers rather than publishing personal names or email addresses.

The system separates internal authentication identifiers from information exposed to other users.

### Architecture

```text
Next.js / React
       |
       v
Application API
       |
       +---- Firebase Auth
       +---- Firestore
       |
       v
Messaging / Matchmaking / Moderation
```

A delayed-delivery workflow allows messages to become visible at a scheduled time rather than immediately.

### Engineering lessons

GlobeTalk gave me experience working with:

- Authentication flows
- NoSQL data modelling
- API boundaries
- Asynchronous application behaviour
- Moderation and reporting
- Testing frontend behaviour
- CI and deployment
- Privacy-oriented product design

[View repository](https://github.com/usmiso/GlobeTalk){ .md-button }

## Why this project matters

GlobeTalk demonstrates my ability to take a product concept beyond a static interface and build the **application logic, data model, user flows and supporting infrastructure** needed to make it functional.
