# Start Command

Get ready to code! This command helps you quickly set up your development environment and get started with your project.

## Actions:
- Check project status
- Show current directory structure  
- Display any package.json scripts if available
- Show git status if in a git repo

Let me help you get started with this project:

## Package Information
@package.json

## Git Status
!git status 2>/dev/null || echo "Not a git repository"

## Available Scripts
![ -f package.json ] && echo "Available package scripts:" && cat package.json | grep -A 20 '"scripts"' || echo "No package.json found"

Ready to start coding! What would you like to work on?
