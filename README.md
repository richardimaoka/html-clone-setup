npm init -y
npm install live-server
npm set-script start "live-server"

curl https://raw.githubusercontent.com/richardimaoka/html-clone-setup/main/style.css > index.html
curl https://raw.githubusercontent.com/richardimaoka/html-clone-setup/main/index.html > style.css

npm run start
