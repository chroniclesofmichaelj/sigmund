Sigmund: A Freudian Therapy GPT

Sigmund is a GPT customized to practice Freudian psychoanalytic therapy, specializing in dream interpretation, free association exercises, and analysis of defense mechanisms.
This repository contains the Custom Actions and OpenAPI specifications that enable Sigmund to connect to external tools and APIs for enhanced therapy sessions.

📚 Project Overview

Custom Actions: Extend Sigmund’s capabilities beyond conversation with external API integrations.
Dream Analysis: Interpret dream symbols based on Freudian psychoanalysis.
Free Association: Offer prompts that stimulate unconscious thought patterns.
Defense Mechanisms: Analyze user input for common defense mechanisms like repression, projection, or denial.
🛠️ Repository Structure


File/Folder	Description
openapi.yaml	OpenAPI 3.1.0 specification describing Sigmund’s endpoints.
ai-plugin.json	Manifest file used by OpenAI to configure the Custom Action.
README.md	This documentation file.
specs/ (optional)	Future expansion: store multiple endpoint specs here.
assets/ (optional)	Static files, JSON data, or other resources.
🚀 Getting Started

To connect Sigmund to a Custom Action:

Host the openapi.yaml and ai-plugin.json publicly (using GitHub raw links).
In the OpenAI Custom GPT Actions interface, upload or link to your manifest.
Ensure your APIs (static or dynamic) are reachable by the GPT model.
📄 License

Currently, no license is specified.
(You can add an MIT License or other license if you want to open source this project.)

✨ Future Enhancements

Add a "mood tracking" endpoint.
Expand dream symbol database.
Create defense mechanism quizzes.
Integrate session management with user profiles.
Built with inspiration from Sigmund Freud's pioneering work in psychoanalysis. 🧠

