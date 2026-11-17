# QuizQuest — Interactive Quiz App

A responsive quiz app made with HTML, CSS and vanilla JavaScript.

## Features
- 10 multiple-choice questions
- 20-second countdown timer per question
- Instant correct/incorrect feedback and explanations
- Automatic timeout handling
- Progress bar and question counter
- Final score, accuracy and correct-answer summary
- Restart quiz
- Responsive mobile and desktop layout
- No framework or build step required

## Run locally
Extract the ZIP, open this folder in VS Code, then open `index.html` in a browser. You can also use VS Code Live Server.

## Test checklist
- [ ] Question and four options load
- [ ] Selecting an answer shows instant feedback
- [ ] Correct and incorrect answers are highlighted
- [ ] Next question advances
- [ ] Timer counts down and timeout is handled
- [ ] Final score and accuracy appear
- [ ] Play again restarts the quiz
- [ ] Mobile layout works

## Deploy with Vercel (PowerShell)
```powershell
npm install -g vercel
vercel login
vercel
vercel --prod
```
Accept static-site detection and use `./` as the project directory.

## GitHub
Create an empty GitHub repository, then run:
```powershell
git init
git add index.html style.css script.js README.md
git commit -m "Build interactive QuizQuest app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
git push -u origin main
```

## Technologies
HTML5 · CSS3 · JavaScript · DOM Manipulation · Event Handling · setInterval
