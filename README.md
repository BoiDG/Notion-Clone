
# Jotion

A notion clone Full stack web app hosted on vercel with next js for the frontend and convex for the backend


## Features

- Real-time database 🔗
- Notion-style editor 📝
- Light and Dark mode 🌓
- Infinite children documents 🌲
- Trash can & soft delete 🗑️
- Authentication 🔐
- File upload
- File deletion
- File replacement
- Icons for each document (changes in real-time) 🌠
- Expandable sidebar ➡️🔀⬅️
- Full mobile responsiveness 📱
- Publish your note to the web 🌐
- Fully collapsable sidebar ↕️
- Landing page 🛬
- Cover image of each document 🖼️
- Recover deleted files 🔄📄

## Technology used
- Convex: Convex is a Backend Application Platform.
- Clerk: Clerk is a cloud-based authentication service that aims to simplify the integration of secure authentication in web applications.
- Edgestore: Cloud-based Object storage system
- Next.js: A React framework for building web applications. It is used for both the frontend and the backend of the application.
- Tailwind CSS: A utility-first CSS framework for rapidly building custom designs. It is used for styling the application.
- TypeScript:  A statically typed superset of JavaScript. It is used for writing the code.
- Mongoose: An Object Data Modeling (ODM) library for MongoDB and Node.js. It is used for defining the product schema and interacting with the MongoDB database.


## Acknowledgements

 - [Learned from AntonioErdelja](https://github.com/AntonioErdeljac/notion-clone-tutorial)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [This readme generator](https://readme.so/)


# Setup
## Installation

```bash
  https://github.com/BoiDG/Notion-Clone.git
```

Install package with npm

```bash
  npm install
```
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

Deployment used by `npx convex dev`
```bash
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

setup Convex

run this to start the database

```bash
npx convex dev
```

start the app
```bash
npx run dev
```
# Setup
## Installation

```bash
  https://github.com/BoiDG/Notion-Clone.git
```

Install package with npm

```bash
  npm install
```
