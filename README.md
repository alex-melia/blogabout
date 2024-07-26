
[![BlogAbout](https://github.com/user-attachments/assets/2348a0c9-901e-4480-b3b6-3e21efd9e91e)](https://blogabout.vercel.app)

# BlogAbout - Serverless Blogging Platform


## Introduction

BlogAbout is the site where you can blog about anything. It is a web application that automatically transforms markdown into fully-formatted blog posts.

## Tech Stack

- Next.js 14
- MongoDB
- NextAuth
- TailwindCSS
- Remark

## Getting Started

1. **Clone & create the repository**

```bash
npx create-next-app my-project-name --example "https://github.com/alex-melia/blogabout"
```

2. **Install the dependencies**

```bash
npm install
```

3. **Set up environment variables**

```bash
cp .env.example .env.local
```

Specify environment variables

I used cloudinary to store images, feel free to use your choice of storage

```bash
MONGODB_URI="MONGO_URI"
CLOUDINARY_CLOUD_NAME="CLOUDINARY_CLOUD_NAME"
CLOUDINARY_API_KEY="CLOUDINARY_API_KEY"
CLOUDINARY_API_SECRET="CLOUDINARY_API_SECRET"
NEXTAUTH_SECRET="NEXTAUTH_SECRET"
NEXTAUTH_URL="NEXTAUTH_URL"
GITHUB_SECRET="GITHUB_SECRET"
GITHUB_ID="GITHUB_ID"
BASE_URL="BASE_URL"
NODE_ENV="NODE_ENV"
```

## Running the App

1. **Starting client and server**

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
