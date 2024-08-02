# AdventureBot 👋

Will be available  soon.



## How to Install 🚀
Requirements 📦 :
- 🐰 Node.js >= 20.10
- 🐍 Python >= 3.11

Build and Install 🛠️

Run the following commands to install:

For Linux/macOS:
```
git clone this project
cd AdventureBot/

# Copying required .env file
cp -RPp .env.example .env

# Building Frontend Using Node
npm install
npm run build

cd ./backend

# Optional: To install using Conda as your development environment, follow these instructions:
# Create and activate a Conda environment
conda create --name advbot-env python=3.11
conda activate advbot-env

# Install dependencies
pip install -r requirements.txt -U

# Start the application
bash start.sh
```

For Windows:

```
git clone this project

cd AdventureBot/

copy .env.example .env

npm install
npm run build

cd .\backend

# Optional: To install using Conda as your development environment, follow these instructions:
# Create and activate a Conda environment
conda create --advbot-env python=3.11
conda activate advbot-env

pip install -r requirements.txt -U

start.bat
```

You should have Adventure Bot up and running at http://localhost:8080/. Enjoy!

---

Created by [ZD AI Lab](https://huggingface.co/zdAI) - Let's make Open Web UI even more amazing together! 💪
