
# Website link : https://codex-metamachin.vercel.app/
# Download CodeX android app : https://github.com/metamachin/openai_codex/raw/main/MetaX%20-%20Your%20AI%20Assistant.apk

# GitHub repo link : https://github.com/metamachin/openai_codex 
# Convert your website to link : https://www.appilix.com/


# Build and Deploy Your Own ChatGPT AI Application That Will Act As Your Assistant.
![Open AI CodeGPT](https://i.ibb.co/LS4DRhb/image-257.png)

# Youtube tutorial of original author : https://youtu.be/2FeymQoKvrk 

# To deploy your app - use https://render.com -> New -> Web Service -> Add env vars

# Deploy frontend on vercel.com

# How to develop locally :- Tools needed - VS Code editor, Git, Chrome Browser
-> Open repo in VS Code
-> Open client/script.js and change render.com URL to localhost:5000
-> Open terminals -> cd server, npm install, npm run dev (Server should be able to listen)
-> Open new terminal -> cd client, npm install, npm run dev (Client should be able to send req from port 5173 to server port 5000)

# How to push your commit and update app :- 
-> Change localhost (line 91) to render.com URL in client/script.js/
-> Save every file/folder
-> git add .
-> git commit -m "Your commit message"
-> git push
-> Go to render.com and manually deploy latest commit.

# How to deploy on your own  :-
  Tools needed -> Github Repo (https://github.com/), OpenAI ChatGPT API Keys (https://chat.openai.com/), Backend hosting (https://render.com/), Frontend hosting (https://vercel.com/)
