# GIT ADVENTURE GAME
Complete 5 levels to master Git!

HOW TO PLAY:
1. Start: ./start-game.sh
2. Read level: cat levels/level1.txt
3. Do tasks in terminal
4. Check: ./check-level.sh
5. Next: ./next-level.sh 2
Complete all levels to win!

🎮 Git Adventure Game - Learn Git by Playing!
A fun, interactive game to master Git commands through hands-on practice. Complete 5 levels and become a Git pro!

🚀 Quick Start

Option 1: One-Command Setup (Easiest!)

# Copy and paste this entire command:
 -c 'mkdir -p git-game && cd git-game && curl -O https://raw.githubusercontent.com/yourusername/git-game/main/setup.sh && chmod +x setup.sh && ./setup.sh'

 
Option 2: Manual Setup

# 1. Clone the game
git clone https://github.com/sakirmansuri/Git_Game_By_Sakir_Mansuri
cd git-adventure-game

# 2. Make scripts executable
chmod +x *.sh

# 3. Start playing!
./start-game.sh

📖 How to Play
🎯 Game Objective

Complete all 5 levels by following instructions and running Git commands in your terminal. Each level teaches essential Git skills!

🕹️ Game Controls
Command	What it does
./start-game.sh          	---Starts the game
cat levels/level1.txt     ---	Read level instructions
./check-game.sh	          ---Check your progress
./git-help.sh	            ---Get Git command hints
./next-level.sh 2	        ---Jump to level 2

🏆 The 5 Levels
Level 1: Git Basics - init, add, commit

Level 2: Tracking Changes - status, diff, log

** Level 3**: Branching - branch, checkout, merge

Level 4: Remote Repositories - Connect to GitHub

Level 5: Tagging & Release - tag, version control



🎮 Step-by-Step Walkthrough
📍 Starting the Game

# Go to the game folder
cd git-adventure-game

# Launch the game
./start-game.sh

# Read Level 1 instructions
cat levels/level1.txt
✅ Level 1 - Your First Commit

# Set your identity (do this once)
git config user.name "Your Name"
git config user.email "you@example.com"

# Start tracking this folder
git init

# Create your first file
echo "Once upon a time..." > story.txt

# Stage the file
git add story.txt

# Commit with a message
git commit -m "Begin the adventure"

# Mark level complete
echo "LEVEL1_DONE" > level1.check
📊 Check Your Progress

# See which levels you've completed
./check-game.sh

# Output will show:
# ✅ Level 1: Complete!
# ❌ Level 2: Not started
# ❌ Level 3: Not started
# ...and so on
🆘 Need Help?

# Show all Git commands used in the game
./git-help.sh

# Get hints for current level
cat levels/level1.txt | grep -A2 "TASKS:"
🎯 Winning the Game
🏁 Complete All Levels
Finish all 5 levels to see the victory message:


./check-game.sh
# 🎉 YOU WIN! Git Master! 🎉
📈 What You'll Learn
Skill	Command	Real-world Use
Start projects	git init	Begin new repositories
Save changes	git commit	Version control
Track files	git status	See what changed
Compare versions	git diff	Review code changes
Work in parallel	git branch	Develop features separately
Combine work	git merge	Integrate team changes
Backup online	git push	Save to GitHub
Mark releases	git tag	Version releases

⏱️ Quick Demo (5 minutes)

# Super quick version for demos
mkdir quick-git && cd quick-git
git init
echo "# Project" > README.md
git add .
git commit -m "First commit"
git checkout -b feature
echo "New feature" > feature.txt
git add . && git commit -m "Add feature"
git checkout main
git merge feature
git log --oneline

👥 Group Activity Ideas
Pair Programming: One person reads instructions, other types

Speed Run: Who can complete all levels fastest?

Debug Challenge: Instructor introduces errors, students fix

Extension Challenge: Add your own Level 6!

🛠️ Customize the Game
Add Your Own Level
bash
# Create Level 6
cat > levels/level6.txt << 'EOF'
=== LEVEL 6: BONUS CHALLENGE ===

Create a GitHub repository and push your game!

Tasks:
1. Go to github.com and create new repo
2. Add remote: git remote add origin YOUR-URL
3. Push code: git push -u origin main
4. Share link with friends!

Complete when: echo "LEVEL6_DONE" > level6.check
EOF

# Add to check script
echo '[ -f "level6.check" ] && echo "✅ Level 6: Complete!" || echo "❌ Level 6: Bonus level"' >> check-game.sh
Change Game Theme
Edit any level file to match your interests:

Fantasy: "Save the kingdom with Git commands!"

Space: "Navigate the Git galaxy!"

Detective: "Solve mysteries with Git clues!"

❓ Frequently Asked Questions
🤔 "I get 'command not found' error"
Make scripts executable:


chmod +x *.sh
🤔 "Git says 'Please tell me who you are'"
Set your identity first:


git config --global user.name "Your Name"
git config --global user.email "you@example.com"
🤔 "How do I start over?"

# Delete all check files
rm -f *.check

# Or reset completely
cd ..
rm -rf git-adventure-game
git clone https://github.com/yourusername/git-adventure-game.git
🤔 "Can I play without GitHub?"
Yes! Level 4 has both options:

With GitHub: Connect to real repository

Without GitHub: Practice with local tags

📚 Learning Resources
Git Basics Cheat Sheet

# Always useful commands
git status                  # What's happening?
git log --oneline          # History summary
git diff                   # See changes
git checkout -- file.txt   # Undo changes
git reset HEAD~1           # Undo last commit
Next Steps After Game
Real Project: Create a personal website repo

Collaborate: Fork a project on GitHub

Advanced: Learn rebase, stash, cherry-pick

Visual Tools: Try GitHub Desktop or GitKraken

👥 Contributing
Found a bug? Have a cool level idea?

Fork this repository

Create your feature branch

Commit your changes

Push to the branch

Create a Pull Request

📄 License
This game is open source and free for educational use! Share with students, colleagues, or study groups.


Happy Gitting! 🚀

Star this repo if you found it helpful!
Share with someone learning Git today!

🎯 Quick Reference Card
Situation	                      Command
Start new project	              git init
Save changes	                  git commit -m "message"
See what changed	              git status
View history	                  git log --oneline
Create branch	                  git checkout -b feature
Merge branches	                git merge feature
Upload to GitHub	              git push origin main
Download updates	              git pull
Mark version	                  git tag v1.0

Pro Tip: Type history | grep git to see all Git commands you've used!

Game on!  ⭐
