# Start Command

Get ready to code! This command helps you quickly set up your development environment and get started with your project.

## Actions:
- Check project status
- Show current directory structure  
- Identify project characteristics
- Show git status if in a git repo
- Display any language-specific package scripts if available

Let me help you get started with this project:

## Project Overview
!pwd
!ls -la

## File Structure
!echo "=== Directory tree ===" && \
tree -L 2 2>/dev/null || find . -maxdepth 2 -type d | sort

## All Files
!echo "=== All files in project ===" && \
find . -maxdepth 2 -type f | sort

## Git Status
!git status 2>/dev/null || echo "Not a git repository"

Ready to start coding! What would you like to work on?
