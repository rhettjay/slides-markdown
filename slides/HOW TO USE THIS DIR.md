
Step 1: Build a new presentation project
```bash
cd ~/docs/presentations
## via https://commerce.nearform.com/open-source/spectacle/docs/
npx create-spectacle
## OR via https://slidev.com
npm init slidev@latest
## OR via https://revealjs.com
git clone https://github.com/hakimel/reveal.js.git \
cd reveal.js && npm install \
npm start
# OR via copying prior projects
cp -r ~/docs/presentations/example ~/docs/presentations/${presentation_name}
# OR via https://quarto.org
quarto preview
```

Step 2:
Copy the file and any necessary assets to a new directory 
```bash
cp ${new-slides}.md ~/docs/presentations/${presentation_name}
```

Step 3:
Install dependencies
```bash
npm install &&
npm run dev
```

Step 4:
Make sure the presentation works and have fun!
