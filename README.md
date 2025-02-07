<div align="center">

Website
Discord
Twitter
<h1>Transform Your AI Workflow</h1> <p>Comity AI bridges the gap between your tools and AI services, enabling seamless integration and intelligent task execution.</p> </div><p align="center"> <a href="#why-comity">Why Comity?</a> • <a href="#core-features">Features</a> • <a href="#quick-tour">Demos</a> • <a href="#get-started-in-5-minutes">Quick Start</a> • <a href="#advanced-usage">Advanced</a> </p>
✨ Why Comity?

    Zero Friction: Integrate effortlessly with your existing tools and services.

    Smart Execution: Automatically determine the best tools and actions for each task.

    Long-Term Memory: Leverage persistent memory for personalized and context-aware responses.

    Multi-Tool Integration: Combine the power of web search, calendars, email, and more.

    Secure & Reliable: Built with robust security and failover mechanisms.

🚀 Core Features

Built on cutting-edge foundations:

    🧠 LLM-Powered Intelligence: Utilizes GPT-4 for natural language understanding and task execution.

    🔧 Tool Integration: Seamlessly connects with services like Google Calendar, Spotify, Linear, and more.

    📂 File Management: Read, write, and manage files locally or in the cloud.

    🗣️ Speech Synthesis: Convert text to speech using ElevenLabs.

    🔍 Advanced Search: Index and search content with Algolia and Qdrant.

    💾 Persistent Memory: Store and retrieve information for long-term context.

🎯 Quick Tour

Explore what Comity AI can do:

    📅 Calendar Assistant - Manage events and schedules.

    🎵 Music Controller - Play and control Spotify playback.

    📧 Email Automation - Send and manage emails.

    🗺️ Map Navigator - Find places and directions.

    💼 Task Manager - Manage tasks and projects with Linear.

    
Get Started in 5 Minutes

    Clone the Repository:
    bash
    Copy

    git clone https://github.com/comityai/comity.git
    cd comity

    Install Dependencies:
    bash
    Copy

    bun install

    Configure Environment Variables:
    bash
    Copy

    cp .env.example .env
    # Set your API keys and configurations in the .env file

    Set Up the Database:
    bash
    Copy

    bun generate
    bun migrate
    bun seed

    Run the Application:
    bash
    Copy

    bun run dev

    Start Interacting:

        Access the web interface at http://localhost:8080.

        Use the /api/agi/chat endpoint for API interactions.

🛠️ Advanced Usage

🔧 Tool Configuration

Customize and extend Comity AI's capabilities by adding new tools:

    Create a new tool in src/services/tools.

    Add the tool configuration in src/config/tools.config.ts.

    Describe the tool's usage in src/database/seed.ts.

🧠 Memory Management

Comity AI supports long-term memory for personalized interactions:

    Store user preferences, past interactions, and contextual data.

    Retrieve and utilize memory for more accurate and relevant responses.

🔄 Task Execution Modes

Comity AI operates in two modes:

    Fast-Track: Directly answers queries using the LLM's knowledge.

    Thinking: Plans and executes tasks using integrated tools and memory.

📊 Watch It Work

Monitor and visualize Comity AI's operations:
mermaid
Copy

graph LR
    A[User Query] --> B[Comity AI]
    B --> C[LLM Processing]
    B --> D[Tool Execution]
    B --> E[Memory Retrieval]
    B --> F[Response Generation]

    Performance Metrics: Track system performance and tool usage.

    Request Tracing: Analyze detailed logs for debugging and optimization.

🌟 Community & Support
<div align="center">

GitHub Stars
Twitter Follow
</div>

    🐦 Twitter Updates

    📧 Email Support

<div align="center"> <sub>Built with ❤️ by the Comity AI team</sub> </div>