
# Website link : https://codex-metamachin.vercel.app/
# Download CodeX android app : https://github.com/metamachin/openai_codex/raw/main/MetaX%20-%20Your%20AI%20Assistant.apk

# GitHub repo link : https://github.com/metamachin/openai_codex 
# Convert your website to link : https://www.appilix.com/


# Build and Deploy Your Own ChatGPT AI Application That Will Help You Code
![Open AI CodeGPT](https://i.ibb.co/LS4DRhb/image-257.png)

# Youtube tutorial : https://youtu.be/2FeymQoKvrk 

# To deploy your app - use https://render.com -> New -> Web Service -> Add env vars

# Deploy frontend on vercel.com

# How to push your commit and update app :-
-> Register on Google, Github, Render.com, Vercel.com.

-> Change localhost (line 91) to render.com URL in client/script.js/
-> Save every file/folder
-> git add .
-> git commit -m "Your commit message"
-> git push
-> Go to render.com and manually deploy latest commit.

# How to develop locally :-
-> Open repo in VS Code
-> Open client/script.js and change render.com URL to localhost:5000
-> Open terminals -> cd server, npm install, npm run dev (Server should be able to listen)
-> Open new terminal -> cd client, npm install, npm run dev (Client should be able to send req from port 5173 to server port 5000)
