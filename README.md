Executive Overview
Smart Subscription & AutoPay Manager
Manage your recurring subscriptions and keep track of upcoming payments from one place.


</div>📌 About the Project
Executive Overview is a subscription management web application concept designed to help users organize and monitor recurring payments across different digital services.

With subscriptions spread across streaming platforms, shopping services, software tools, and other applications, it can be difficult to remember renewal dates and keep track of recurring expenses. Executive Overview aims to bring this information together in a single dashboard.

The project also explores PayPal integration to support payment-related workflows and make subscription management more convenient.
✨ Key Goals
- Centralized subscription tracking — keep subscription information organized in one place.
- Payment visibility — review recurring expenses and upcoming payment dates.
- Subscription organization — manage subscriptions across different service categories.
- AI-assisted experience — use Gemini-powered capabilities where configured in the application.
- PayPal integration — connect payment workflows with PayPal, subject to the integration and permissions configured for the project.
The exact features available depend on the current deployed version and configured integrations.

🌐 Live Demo
Try the deployed application:

https://executive-overview.onrender.com
🛠️ Tech Stack
The project setup provided by Google AI Studio identifies the following development components:
- Node.js — JavaScript runtime
- npm — dependency management
- Gemini API — AI capabilities (requires an API key)
- Google AI Studio — app development
- Render — deployment and hosting
- PayPal — payment integration
Check the source code and configuration files for the exact frameworks, libraries, and integration versions used.
🚀 Run Locally
Prerequisites
- Node.js installed
- npm (included with Node.js)
- A Gemini API key if the app uses Gemini features
- PayPal developer credentials if you are running PayPal integration locally
1. Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
Replace the repository URL and folder name with your own GitHub details.
2. Install dependencies
npm install
3. Configure environment variables
Create a .env.local file in the project root and add the environment variables required by your source code.

At minimum, the AI Studio starter setup specifies:
GEMINI_API_KEY=your_gemini_api_key
If PayPal credentials are required, add the variable names expected by your implementation. Do not commit API keys, access tokens, client secrets, or other credentials to GitHub.
4. Start the development server
npm run dev
Open the local URL printed in your terminal (commonly http://localhost:5173, depending on the project configuration).
🔐 Security Notes
- Keep .env.local and other secret files out of version control.
- Add secret files to .gitignore.
- Store production credentials in Render's Environment settings, not directly in source code.
- Use PayPal sandbox credentials for development and testing.
- Never expose PayPal client secrets or private API keys in browser-side code.
🚢 Deployment
The live application is hosted on Render.

To deploy your own copy:
1. Push the project to a GitHub repository.
2. Sign in to Render and create a service connected to that repository.
3. Configure the build and start commands according to the project's package.json.
4. Add the required environment variables in the Render dashboard.
5. Deploy and test the generated public URL.
For a frontend-only application, configure it as a Static Site if the project build output and routing support that setup. If it requires a Node.js server, deploy it as a Web Service.
🧪 Current Project Status
The application has a public deployment. Review the live demo and repository source code for the latest implemented functionality and integration status.
🤝 Contributing
Contributions and suggestions are welcome.
1. Fork the repository.
2. Create a feature branch: git checkout -b feature/your-feature
3. Commit your changes: git commit -m "Add your feature"
4. Push the branch: git push origin feature/your-feature
5. Open a Pull Request.
⚠️ Disclaimer
Executive Overview is an independent project. It is not an official PayPal product and is not affiliated with or endorsed by PayPal. Any PayPal functionality is subject to PayPal's API, account eligibility, permissions, and applicable terms.
📄 License
No license has been specified yet. Add a LICENSE file before allowing others to reuse, modify, or distribute this project.
<div align="center">Built to make recurring payments easier to understand and manage.
</div>
