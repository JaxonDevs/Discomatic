# Discomatic

Discomatic is a full-stack Discord clone application, following the tutorial by Code With Antonio.

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) 

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/JaxonDevs/Discomatic.git
   cd Discomatic
   ```

  2. Install the dependencies:
```bash
  npm install
   ```

  3. Setup .env 
Make a .env file in the projects root directory
and make it include
```bash
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
   ```

[Clerk](https://clerk.com/)

[Supabase](https://supabase.com/)

[UploadThing](https://uploadthing.com/)

[LiveKit](https://livekit.io/)   (HAVE NOT TESTED PROPERLY)

4. Time to run it:
   ```bash
   npm run dev
   ```
