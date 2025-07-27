# Clasicos

I am a developer with commercial experience who built the non-commercial web application **Clasicos** using NestJS and Next.js - https://clasicos.pl.

## What is Clasicos?

Clasicos is a neutral meeting place for fans of both Barcelona and Real Madrid.  

- Users can create their all-time best XI from a pool of players stored in our database.  
- If a player they want isn’t available, they can fill out a short suggestion form to request adding that player. Suggestions are emailed directly to the admin.
- All other user-submitted data (teams, comments, recommendations, etc.) is stored in the database.

## Tech Stack & Design

- **Design (Figma)**: big thanks to [@njqnik](https://github.com/njqnik) - thanks to the polished Figma design I could fully focus on frontend, backend and deployment.  
- **Backend**: NestJS (https://github.com/AdamIlnicki24/clasicos-api)  
- **Frontend**: Next.js (https://github.com/AdamIlnicki24/clasicos-web)  

Each repo has its own detailed README - feel free to check them out!

## Admin Features

- Ban users for any behavior deemed offensive (prevents them from commenting and recommending).
- Delete comments.  
- Add players to the database.

## Why This Idea?

I’ve spent 17 years on similar fan sites and watched them evolve rapidly. Rather than build yet another club-specific fan page, I wanted to create a truly neutral space where Polish fans of both Barcelona and Real Madrid could gather.  

Most popular Polish Barcelona and Real Madrid sites have active forums with high posting frequency. Clasicos offers the same - users can post comments and recommend others’ comments. Offensive behavior is policed by admins, who can ban users to keep the community welcoming.

## Branching & Deployment

- **Development**: All work and commits happen on the `dev` branch.  
- **Main**: Pull requests are merged into `main`.  
- **Deployment**: The `main` branch is connected to Vercel for automatic deployments with CI.
