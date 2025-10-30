Meet AI

An AI-powered meeting scheduling platform built with Next.js, allowing users to seamlessly schedule, manage and participate in meetings via smart agents.

<img width="1275" height="763" alt="image" src="https://github.com/user-attachments/assets/0aebebbf-84cd-48d6-ba21-9984812f0b0d" />


🚀 Demo

Live site ➜ https://meetai-iota.vercel.app/

💡 Features

Intuitive login/signup workflow (e.g., via email or OAuth)

Intelligent agent suggests ideal meeting times based on participants’ availability

Easy creation of meeting links and invitation management

Dashboard to view scheduled meetings, upcoming sessions, and meeting history

Responsive design: works on desktop & mobile

Built with scalability and SaaS in mind

Deployed on Vercel for fast and global delivery

<img width="1918" height="863" alt="image" src="https://github.com/user-attachments/assets/6b3c199f-a620-4d11-be51-b43aceff3464" />


🧱 Tech Stack

Framework: Next.js (React)

Hosting / Deployment: Vercel

Authentication: (e.g., NextAuth.js or custom email/OAuth)

UI: Tailwind CSS / Chakra UI (or whichever you’re using)

Backend / APIs: Next.js API routes or serverless functions

Database / Storage: (e.g., PostgreSQL, MongoDB, Firebase — update as appropriate)

Agent / Scheduling Logic: Custom business logic + external APIs (e.g., Google Calendar, Microsoft 365)

Version Control: Git + GitHub

🛠 Installation & Local Setup
# Clone the repository
git clone https://github.com/YourUsername/Meet-AI.git

# Move into the project directory
cd meetai-saas-ai-agent-platform-nextjs-main

# Install dependencies
npm install
# or
yarn install

# Create a .env.local file with required environment variables, e.g.:
NEXT_PUBLIC_APP_URL=https://meetai-iota.vercel.app
DATABASE_URL=your_database_url
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
JWT_SECRET=some_long_secret

# Run the development server
npm run dev
# or
yarn dev

# Open http://localhost:3000 in your browser

✅ Usage

Sign up or log in to the platform.

Connect your calendar (if applicable) so that the system can read your availability.

Create a meeting event by specifying attendees, duration, and preferred time slots.

Let the AI agent recommend the best time and send invitations.

Manage your meetings via the dashboard — reschedule, cancel or view details.

🔐 Environment Variables

Here are some of the key environment variables you’ll need to define in .env.local:

Variable	Description
DATABASE_URL	Connection string to your database
GOOGLE_CLIENT_ID	OAuth client ID for Google sign-in
GOOGLE_CLIENT_SECRET	OAuth client secret for Google sign-in
JWT_SECRET	Secret key used for signing JWT tokens
NEXT_PUBLIC_APP_URL	The public URL of your deployed app
📦 Deployment

The project is configured for deployment on Vercel
.

Push your code to the main branch (or your configured branch) on GitHub.

Connect the repository to Vercel.

Set environment variables in Vercel dashboard.

Vercel will build and deploy the site automatically.

🧩 Contributing

Contributions are welcome!
Please follow these steps:

Fork the repository.

Create a new branch: git checkout -b feature/YourFeatureName.

Make your changes.

Commit your changes: git commit -m "Add YourFeatureName".

Push to your branch: git push origin feature/YourFeatureName.

Open a Pull Request describing your changes and why they’re needed.

📄 License

(Mention your license here, e.g., MIT License)

MIT License
Copyright (c) 2025 [Your Name]
...

❓ Frequently Asked Questions (FAQ)

Q: Can I connect multiple calendars (Google, Outlook)?
A: Yes — (if implemented) you can add multiple calendar providers from the settings page.

Q: How does the AI agent choose time slots?
A: The agent analyses participants’ availability, preferred time windows, duration and meeting priority to select optimal time slots.

Q: Is there a free tier?
A: (Update based on your business model) Yes — the free tier allows X meetings/month; premium tier unlocks Y features.

<img width="1522" height="685" alt="image" src="https://github.com/user-attachments/assets/b9a3f652-e64d-42a8-aed2-d147d87a38ca" />


📝 Acknowledgements

Built using Next.js

UI guided by Tailwind CSS

Deployed via Vercel

Special thanks to [Your Name], [Contributors], and open-source community
