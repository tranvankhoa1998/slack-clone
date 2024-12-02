
Welcome to the Ultimate Next.js 15, TypeScript and Supabase Course! In this course, I'll try to replica the slack.com ( a project of my company)

## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js (v14 or later)
- Bun (latest version) or you can use npm or what works for you
- Git
- To replica my project make sure follow package.json and database you need to create own one
- If you want to take a look , access my hosting URL:https://slack-clone-eta-vert.vercel.app Note : don't uploading somethings to much on my website ( all cloud i used is free, so the data provided is quite little )
## Getting Started

Follow these steps to set up the project:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/tranvankhoa.1998/slack-clone.git
   cd slack-clone
   ```

2. **Install Dependencies:**

   ```bash
   bun install
   ```
   ```bash
   npm install ( if you don't want to install bun )
   ```
3. **Set Up Environment Variables:**

   - Create a `.env.local` and fill in the required environment variables.

4. **Run the Development Server:**

   ```bash
   bun dev
   ```
   ```bash
   npm run dev 
   ```

   Your app should now be running on [http://localhost:3000](http://localhost:3000).

## Course Structure

This course is divided into multiple modules, each covering different aspects of building the Slack clone. The modules include:

- Setting up Next.js and TypeScript
- Configuring Supabase (RPC, Storage, SQL, Role Level Security)
- Styling with Tailwind CSS and Shadcn UI
- Implementing Authentication (Google Auth, GitHub Auth, Email Auth with Magic Link)
- Managing state with Zustand and React Hook Form
- Real-time communication with Socket.IO
- Handling file uploads with Uploadthing and Supbase Storage
- Advanced Next.js features and middleware

## Resources

### SQL Scripts

All SQL scripts used in this course can be found in the `sql.txt` file. These scripts will help you set up your database schema, functions, and other necessary configurations.

### Documentation Links

For detailed documentation and additional resources, refer to the `docs.tsx` file. This file contains links to various documentation pages for the libraries and tools used in this course.

### Environment Variables

Make sure to properly configure your environment variables by referring to the `.env.local` file. This file contains example values and instructions on what needs to be filled in.
## My demo video 
https://www.youtube.com/watch?v=RqjGZRg6z4c

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request. Contributions are always welcome!

