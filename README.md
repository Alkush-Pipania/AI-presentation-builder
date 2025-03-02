

#Presentation Builder

It is an AI-powered wrapper designed to simplify the process of creating PowerPoint presentations. Leveraging modern tools like **Bun**, **Clerk**, and **Neon**, GOOG aims to streamline presentation creation with AI assistance for content generation, design suggestions, and more.

## 🚀 Features
- AI-generated presentation slides
- Easy authentication with Clerk
- Lightning-fast performance powered by Bun
- PostgreSQL database management with Neon

## 🛠 Tech Stack
- **Bun** - All-in-one JavaScript runtime (bundler, transpiler, package manager)
- **Clerk** - Authentication and user management
- **Neon** - Serverless Postgres for database storage
- **OpenAI API** (or other AI models) - For AI-powered content generation

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Alkush-Pipania/GOOG
   cd GOOG
   ```

2. **Install dependencies using Bun:**
   ```bash
   bun install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following:
   ```env
   CLERK_API_KEY=your_clerk_api_key
   DATABASE_URL=your_neon_database_url
   OPENAI_API_KEY=your_openai_api_key
   ```

4. **Run the development server:**
   ```bash
   bun dev
   ```

## 📋 Usage

1. **Sign up or log in** using Clerk's authentication.
2. **Enter your presentation topic** and let the AI generate slide content.
3. **Download** the presentation in PPT format or customize it as needed.

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to improve the project.

