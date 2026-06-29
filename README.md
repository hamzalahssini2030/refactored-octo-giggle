# Prompt Engineer — Loria Space Smart Prompt Console

**Prompt Engineer** is a single-file HTML web tool designed to help users create clear, structured, and professional prompts before sending them to AI platforms.

The project does **not** run an AI model inside the browser and does **not** require an API key. Instead, it works as a smart prompt-building assistant: it guides the user through a simple process, collects the needed details, generates a complete prompt, and lets the user copy or export it.

## What This Tool Does

Prompt Engineer helps users describe exactly what they want from an AI tool. It turns scattered ideas into a complete, organized prompt that can be pasted into ChatGPT, Gemini, Claude, image generators, video tools, coding assistants, or other AI platforms.

The interface is built around three clear steps:

1. **Choose the output type**
   The user selects what they want to create, such as text, code, website, web app, mobile app, dashboard, image, logo, presentation, social media post, PDF/DOCX file, video, audio, translation, automation, consultation, or another custom request.

2. **Fill the project details**
   The tool asks for useful information such as the idea, role, target audience, features, design preferences, colors, fonts, dimensions, language, expected result, references, attachments, and extra notes.

3. **Generate and export the prompt**
   The final prompt can be copied directly or exported as **HTML**, **PDF**, or **DOCX**.

## Main Features

* Single HTML file.
* No backend required.
* No API key required.
* Works locally in the browser.
* Multi-language interface:

  * English
  * Arabic
  * French
  * Italian
  * German
* Dark mode and light mode.
* Smart Fill system to pre-fill fields based on the selected request type.
* Keyword prediction to suggest the most suitable output category.
* Prompt strength meter.
* Support for multiple output types.
* Optional advanced fields.
* File and image attachment support.
* Sketch/drawing area to explain an idea visually.
* Voice input support in compatible browsers.
* Copy prompt to clipboard.
* Export prompt as HTML.
* Export prompt as PDF through the browser print window.
* Export prompt as DOCX using the included DOCX library.
* Local browser storage to keep draft data.
* Reset option to clear saved data.
* Recommended AI tool links based on the selected output type.

## Supported Request Types

The tool includes prompt templates for many use cases, including:

* Plain text
* Specialised consultation
* Code
* Full website
* Web app
* Mobile app
* Dashboard
* Service or information request
* Image
* Logo
* Presentation
* Social media post
* File creation
* Video
* Audio
* Format conversion
* Specialised translation
* Automation JSON
* Answer from files
* Fast learning roadmap
* Custom song
* Invention or idea generation
* Custom request

## How It Works

The user selects the type of output they want, adds the necessary information, and the tool builds a complete AI prompt using a clear structure.

The generated prompt includes:

* The role the AI should take.
* The exact task.
* Project details.
* Required features.
* Design and formatting preferences.
* Target audience.
* Language requirements.
* Attached file instructions.
* Mandatory quality rules.
* Expected final result.

This makes the final prompt more precise, more complete, and easier for AI systems to understand.

## Attachments and Sketch Support

The tool allows users to attach images, files, audio, video, or other assets. When exporting as HTML, PDF, or DOCX, attachments can be included so the user can send a richer prompt package to an AI platform.

It also includes a simple sketch canvas. The user can draw a rough idea, attach it to the prompt, and explain visual intent without needing professional drawing skills.

## Voice Input

On supported browsers such as Chrome or Edge, the tool can use browser speech recognition to let the user dictate text into some fields.

This is useful for users who prefer speaking instead of typing.

## Export Options

The final prompt can be exported in different formats:

* **Copy text** — for quickly pasting into an AI chat.
* **HTML** — useful when attachments or visual references are included.
* **PDF** — generated through the browser print window.
* **DOCX** — generated using the DOCX JavaScript library.

## Local Storage

The tool saves draft data in the browser using local storage. This means the user can continue working without losing progress.

No server database is required.

## Important Notes

This project is a prompt-building interface, not an AI model.

It does not generate AI answers by itself. It prepares high-quality prompts that the user can paste into external AI tools.

It does not require:

* API keys
* Login system
* Server hosting
* Database setup
* Backend installation

## How to Use

1. Open the HTML file in a browser.
2. Choose the type of output you want to create.
3. Enter keywords or a short description.
4. Click Smart Fill if you want the tool to pre-fill useful fields.
5. Edit the fields according to your real request.
6. Generate the final prompt.
7. Copy it or export it as HTML, PDF, or DOCX.
8. Paste or upload the result into your preferred AI tool.

## Best Use Cases

This tool is useful for:

* Teachers
* Students
* Developers
* Designers
* Content creators
* Social media managers
* Business owners
* Consultants
* Freelancers
* Anyone who wants better AI results without writing prompts from scratch

## Technologies Used

* HTML
* CSS
* JavaScript
* Browser Local Storage
* Web Speech API
* Canvas API
* DOCX JavaScript library

## Project Goal

The goal of Prompt Engineer is to make prompt writing easier, more structured, and more professional.

Instead of asking the user to manually think about every part of a good prompt, the tool guides them step by step and produces a clean final prompt that can be reused across many AI platforms.
