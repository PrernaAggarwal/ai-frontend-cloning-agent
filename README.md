AI-Powered Frontend Cloning Agent

An interactive web dashboard that simulates an autonomous AI agent capable of taking a public website URL, analyzing its layout, generating clean React/Next.js code, providing a live preview, and modifying the frontend via natural language chat prompts.

How to Run

Download or clone this repository containing the index.html file.

Double-click index.html (or right-click and open it with any web browser like Chrome, Edge, or Safari).

No installation, build steps, or API keys are required to test the interactive prototype!

Architecture

Target URL -> DOM & Layout Analysis -> React/Next.js Code Generation -> Build Validation -> Live Sandbox Preview & AI Prompt Modification

Technologies Used

Frontend: HTML5, Vanilla JavaScript

Styling: Tailwind CSS (via CDN)

Icons: Lucide Icons

Fonts: Google Fonts (Inter & Fira Code)

Key Implementation Decisions

Single-File Architecture: Bundled into a lightweight standalone HTML file for instant portability and zero-configuration testing.

Simulated Agent Pipeline: Step-by-step visual progress stream representing URL crawling, DOM parsing, code synthesis, and build checking.

Natural Language Refinement: Interactive chat interface allowing real-time modifications (changing colors, adding testimonials, toggling sticky navbars, or switching hero layouts).

Limitations

Static Prototype Simulation: This frontend interface simulates the AI agent's workflow and state changes locally in the browser rather than connecting to a live backend cloud cluster.

Authenticated Pages: Public URLs protected behind strict login walls or captchas cannot be crawled.
