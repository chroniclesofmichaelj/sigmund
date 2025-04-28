# Sigmund: A Freudian Therapy GPT

Sigmund is a GPT customized to practice Freudian psychoanalytic therapy, specializing in dream interpretation, free association exercises, and analysis of defense mechanisms.  
This repository contains the Custom Actions and OpenAPI specifications that enable Sigmund to connect to external tools and APIs for enhanced therapy sessions.

## 📚 Project Overview

- **Custom Actions**: Extend Sigmund’s capabilities beyond conversation with external API integrations.
- **Dream Analysis**: Interpret dream symbols based on Freudian psychoanalysis.
- **Free Association**: Offer prompts that stimulate unconscious thought patterns.
- **Defense Mechanisms**: Analyze user input for common defense mechanisms like repression, projection, or denial.

## 🛠️ Repository Structure

| File/Folder    | Description                                                           |
|----------------|-----------------------------------------------------------------------|
| `openapi.yaml` | OpenAPI 3.1.0 specification describing Sigmund’s endpoints.            |
| `ai-plugin.json` | Manifest file used by OpenAI to configure the Custom Action.         |
| `README.md`    | This documentation file.                                              |
| `specs/` | Future endpoint specs.               |
| `assets/`  | Static files, JSON data, other resources.                        |

## 🚀 Getting Started

To connect Sigmund to a Custom Action:
1. Host the `openapi.yaml` and `ai-plugin.json` publicly (using GitHub raw links).
2. In the OpenAI Custom GPT Actions interface, upload or link to your manifest.
3. Ensure your APIs (static or dynamic) are reachable by the GPT model.

## 📄 License

MIT License

Copyright (c) 2025 chroniclesofmichaelj

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## ✨ Future Enhancements (to come)
- "Mood tracking" endpoint.
- Expanded dream symbol database.
- Defense mechanism quizzes.
- Integrated session management with user profiles.

Built with inspiration from Sigmund Freud's pioneering work in psychoanalysis. 🧠
