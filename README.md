Nice skills for agents.

## Available Skills

### bilibili-video-summary1

**Search and summarize Bilibili videos with AI subtitles**

#### Overview

This skill enables you to search for videos on Bilibili (B站), sort by play count, extract AI-generated subtitles, and automatically summarize video content. Perfect for discovering and understanding popular video content on Bilibili.

#### When to Use

Use this skill when the user asks to:
- "Search B站 for..."
- "Bilibili search for..."
- "Find videos about X on bilibili"
- "Summarize B站 videos"
- Or similar requests involving Bilibili video discovery and summarization

#### Prerequisites

- Playwright MCP browser is running
- Chrome-for-testing is installed
- If you encounter "Browser not installed" error, clear the npm cache:
  ```bash
  rm -rf ~/AppData/Local/ms-playwright/b/*
  rm -rf ~/AppData/Local/npm-cache/_npx/9833c18b2d85bc59
Getting Started
Project Structure
Code
nice-skills/
└── skills/                           # Directory for all skills
    └── bilibili-video-summary1/      # Bilibili video search and summary skill
How to Add a Skill
Create your skill file or directory in the skills/ directory
Implement your skill functionality
Submit a Pull Request
Contributing
We welcome new skill contributions! Please ensure:

Code is clear and well-documented
Include basic usage instructions
Follow project conventions
