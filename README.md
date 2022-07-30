npm init -y
npm install live-server
npm set-script start "live-server"

echo "node_modules" > .gitignore

curl https://raw.githubusercontent.com/richardimaoka/html-clone-setup/main/style.css > style.css
curl https://raw.githubusercontent.com/richardimaoka/html-clone-setup/main/index.html > index.html

npm run start
