📝 AI-Powered Meeting Notes Summarizer

A modern web app that converts your meeting transcripts into concise AI-powered summaries. You can paste or upload transcripts, generate summaries, and even email them directly.

✨ Features

📄 Paste or upload meeting transcripts

🤖 AI-generated meeting summaries

⚙️ Customizable summary instructions

📧 Send summarized notes via email

🚀 Hosted on Vercel for fast access

🛠 Tech Stack
Technology	Purpose
React / Next.js	Frontend UI and serverless API routes
Node.js	Backend logic
Groq API (LLM)	AI summarization of meeting transcripts
GROQ_API_KEY	Authenticates with Groq API
Nodemailer	Sends email with summaries
Vercel	Hosting frontend & serverless backend
⚡ Installation

Clone the repo:

git clone https://github.com/yourusername/meeting-notes-summarizer.git
cd meeting-notes-summarizer


Install dependencies:

npm install


Create .env file in the root folder:

GROQ_API_KEY=your_groq_api_key
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password


Run the app locally:

npm run dev


Visit: http://localhost:3000

🖥 Usage

Paste or upload a meeting transcript.

Click Generate Summary.

Optional: Enter an email to send the summary.

Copy, edit, or share your AI-generated notes.

🚀 Deployment

This project is optimized for Vercel.

Connect your GitHub repository to Vercel.

Add environment variables in the Vercel dashboard.

Deploy your project with one click.

🤝 Contributing

Fork the repo

Create a branch: git checkout -b feature-name

Commit changes: git commit -m "Add feature"

Push branch: git push origin feature-name

Open a pull request

📂 Folder Structure
├── public/        # Static assets
├── pages/         # Next.js pages
│   ├── api/       # API routes for AI summarization & email
├── components/    # Reusable React components
├── styles/        # CSS / styling
├── .env           # Environment variables (not committed)
├── package.json   # Dependencies & scripts

📄 License

This project is licensed under the MIT License.
