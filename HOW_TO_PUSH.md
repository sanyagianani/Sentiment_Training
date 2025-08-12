HOW TO PUSH THIS TO GITHUB (LOCAL - recommended)
------------------------------------------------
1. Create a repo on GitHub (empty), name it e.g. Sentiment-Training.
2. On your machine:
   git clone https://github.com/<your-username>/Sentiment-Training.git
   cd Sentiment-Training
   # copy the files from this unzip or move them into the cloned folder
   git add .
   git commit -m "Initial commit - Sentiment Training project"
   git branch -M main
   git push -u origin main

NOTES:
- If prompted for a password when pushing via HTTPS, use a GitHub Personal Access Token (PAT).
- Alternatively, set up SSH keys and use the SSH repo URL.
