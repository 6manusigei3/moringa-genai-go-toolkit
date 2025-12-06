# Moringa GenAI Beginner Toolkit – Go (Golang)

## Overview
This project is a beginner-friendly toolkit designed to help new developers get started with Go (Golang) using generative AI.  
It demonstrates a simple Hello World program and documents the setup, AI prompts used, and common issues.

## Features
- Step-by-step Go setup instructions
- Minimal working example (Hello World)
- AI prompt journal to enhance learning
- Documentation of common errors and fixes

## System Requirements
- OS: Linux / Mac / Windows
- Go compiler installed
- Terminal (or VS Code terminal)
- No additional packages required for Hello World

## Installation & Setup
1. Install Go:
   ```bash
   sudo snap install go --classic
## Verify installation:
go version

##Clone the repository:

```bash
git clone https://github.com/6manusigei3/moringa-genai-go-toolkit.git
cd moringa-genai-go-toolkit
##Run the Hello World program:
```bash
go run main.go
## Expected Output
Hello, World!
## Project Structure
bash
Copy code
moringa-genai-go-toolkit/
├── main.go        # Hello World program
├── toolkit.md     # Complete documentation
└── README.md      # Project overview and instructions
## AI Prompt Journal
This project leveraged AI prompts from ai.moringaschool.com to:

Understand Go programming concepts

Guide installation and setup

Explain the Hello World program line by line

## Common Issues & Fixes
Snap install warning about --classic: resolved by running sudo snap install go --classic.

Git commit error due to missing identity: resolved by setting:

```bash
git config --global user.name "Emmanuel Kipchumba Sigei"
git config --global user.email "kipchumbaemmanuel061@gmail.com"
GitHub push requires a Personal Access Token (PAT) instead of a password.

## References
Official Go Docs: https://golang.org/doc/

GitHub Docs: https://docs.github.com/

AI prompts: ai.moringaschool.com

