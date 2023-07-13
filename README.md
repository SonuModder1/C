- Installation -
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs
npm install selenium-webdriver
npm install 2captcha

- Usage -
node ck-browser.js <target> <time> <threads> <proxies>

- Example -
node ck-browser.js https://ckddos.nb 60 20 proxy.txt
