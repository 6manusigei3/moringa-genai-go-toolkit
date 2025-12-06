
# Prompt-Powered Kickstart: Getting Started with Go (Golang)

## 1. Title & Objective
The objective of this project is to use generative AI to learn the basics of Go and build a simple runnable Hello World program.

## 2. Quick Summary of Go
Go is a statically typed programming language developed by Google, commonly used for building backend services and system-level applications.

## 3. System Requirements
- OS: Linux
- Tools: Go, Terminal, VS Code
- Packages: none required for Hello World

---

## 4. Installation & Setup
1. Install Go: `sudo snap install go --classic` (Linux)
2. Verify installation: `go version`
3. Create project folder: `mkdir moringa-genai-go-toolkit && cd moringa-genai-go-toolkit`
4. Create file `main.go` and paste Hello World code.

## 5.Minimal Working Example
**Description:** Prints "Hello, World!" to the terminal.

**Code:**
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}


---

##  6. AI Prompt Journal 

```markdown
**Prompt 1:** "Explain Go (Golang) in simple terms for a beginner. Include what it is used for and one real-world application."
- AI helped me understand Go's purpose and real-world usage.

**Prompt 2:** "Give me step-by-step instructions to install Go on Linux and verify installation."
- AI provided commands for installation and verification.

**Prompt 3:** "Show me how to write and run a simple Hello World program in Go, and explain each part of the code."
- AI guided me to create the code and explained line by line.

## 7.Common Issues & Fixes
- Snap install warning about `--classic`: resolved by running `sudo snap install go --classic`.
- Git commit error due to missing identity: resolved by setting:
git config --global user.name "Emmanuel Kipchumba Sigei"
git config --global user.email "kipchumbaemmanuel061@gmail.com
"
- GitHub push required PAT instead of password: created a Personal Access Token and used it.

## 8.REFERENCES
- Official Go Docs: https://golang.org/doc/
- GitHub Docs: https://docs.github.com/
- AI prompts used: ai.moringaschool.com
