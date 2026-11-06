# GitHub API DevOps Scripts

Bash script to list users with READ-only access to a GitHub repository using GitHub API.

Useful for DevOps Audit & Access Management.

## Files
1. `list-collaborators.sh` - List collaborators with READ access

## How to Run

### Step 1: Set Token
export GITHUB_TOKEN="your_token_here"

export GITHUB_USERNAME="dariyaprathibha"

### Step 2: Run Script
./list-collaborators.sh dariyaprathibha awstoolkit-

## What I Learned
- How to use GitHub API with curl
- How to filter JSON data using jq
- How DevOps engineers audit repo access
- How to protect secrets using .env and .gitignore

Skills: Bash | GitHub API | curl | jq | DevOps Automation