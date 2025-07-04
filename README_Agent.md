# 🤖 Web Scraping AI Agent for Startup & VC Data

An AI-powered agent designed to automate the process of **scraping and populating structured data** (like contact details, emails, websites, etc.) from the web into a spreadsheet — using names of startups, incubators, or VCs as the input source.

---

## 🚀 What It Does

This project uses a **Gemini AI API key** (or any other LLM provider key) to drive a web-browsing agent that:

- Accepts a spreadsheet with startup/VC/incubator names.
- Automatically searches the web for relevant pages.
- Extracts **email, contact info, LinkedIn, website, and other metadata**.
- Fills and updates the sheet with the scraped information.

It’s designed to massively reduce the time taken to compile structured datasets from unstructured online data sources — useful for researchers, investors, startup scouts, and growth hackers.

---

## 🧠 How It Works

- 🧩 Built on **React + TypeScript** using **Vite** for ultra-fast dev experience
- 🎨 Styled with **Tailwind CSS** and **shadcn-ui** components
- 🛠️ AI capabilities powered via **Gemini AI** (requires API key)
- 📤 Supports deployment via **Lovable.dev** and GitHub workflows

---

## ✨ Features

- Import spreadsheet with names of VCs/incubators/startups
- Auto-search and extract online data
- Clean and structured output directly in the spreadsheet
- Supports local development, GitHub Codespaces, or AI prompting via [Lovable](https://lovable.dev)
- Custom domain deployment supported

---

## 🧪 Technologies Used

- React + TypeScript (frontend)
- Vite (build tool)
- Tailwind CSS + shadcn-ui (UI)
- Gemini AI (via API key)
- Lovable.dev (AI prompt interface + deployment)

---

## 🛠️ Development

You can edit the code in multiple ways:

### 1. Prompt-Based Editing via Lovable
[👉 Open in Lovable](https://lovable.dev/projects/aa98fa11-1d7c-4422-af23-d23a06715494)

### 2. Local Development

```bash
git clone <YOUR_GIT_URL>
cd <YOUR_PROJECT_NAME>
npm i
npm run dev
```

Make sure you have **Node.js** and **npm** installed ([Install via nvm](https://github.com/nvm-sh/nvm#installing-and-updating))

### 3. GitHub Codespaces
- Click “Code” > “Codespaces” > “New Codespace” to launch a dev environment

---

## 🌐 Deployment

- One-click publish using [Lovable](https://lovable.dev/projects/aa98fa11-1d7c-4422-af23-d23a06715494)
- Connect custom domain from Project → Settings → Domains

📖 [Custom domain guide](https://docs.lovable.dev/tips-tricks/custom-domain#step-by-step-guide)

---

## 🔐 Environment Variables

- `GEMINI_API_KEY` – required to run the agent
- Optional: Sheet export path, custom selectors or headers

---

## 📦 How to Use

1. Prepare a `.csv` or `.xlsx` file with a column titled `"Company Name"` or `"Incubator"`
2. Define headers like `"Email"`, `"Website"`, `"Contact"` in the next columns
3. Start the agent — it will fill the data for each row by searching online

---

## 📘 License

This project is licensed under the MIT License.

---

> Made to supercharge your startup scouting, research automation, and market intelligence 🔍📊