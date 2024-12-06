**🤑 TENEO-BOT 🤑**
>Installation & Clone the repository to your local machine:

*😴 INSTALL REPOSITORY*

>git clone https://github.com/SRCryptoBoyz/Teneo-bot
cd teneo-bot
npm install

🕐 SETUP ACCOUNT
➡️ Set up account.js, config.js and proxy.txt first before you run the script

➡️ account.js : 
🟡Change the account.js file to set your account parameters, 
➡️ nano accounts.js
🟣Later it will look like this: 👇

module.exports = [
  {
    email: "account1@example.com",
    password: "password1"
  },
  {
    email: "account2@example.com",
    password: "password2"
  },
  // Add more accounts as needed
];
📝 replace with your Teneo account Email and PW,

➡️ PROXY CONFIGURATION: 
🟡 change the config.js file if you want to use a proxy from false to true, if there is no proxy, just leave it as default: 
➡️ nano config.js
🟣Later it will look like this: 👇
const useProxy = false; // (set true if want to use proxy, false if not)

module.exports = {
  useProxy
};

➡️ PROXY SETUP:
🟡Put your proxy into the proxy.txt file 
➡️ nano proxy.tx 
🟣Later it will look like this: 👇
ip:port
username:password@ip:port 
http://ip:port http://username:password@ip:port
(You delete it and replace it with your proxy, to delete the file: CTRL + K)

If you have finished all the setup, just run the script
➡️ node index.js

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
 
🤑 TENEO-BOT 🤑
🇲🇨 Indonesian


💯 Installation & Clone the repository to your local machine:

😴 INSTALL REPOSITORY :
git clone https://github.com/SRCryptoBoyz/Teneo-bot

 
cd teneo-bot

npm install

🕐 SETUP AKUN
➡️ Set up dulu account.js, config.js dan proxy.txt sebelum kalian running script

➡️ account.js : 
🟡Ubah file account.js untuk mengatur parameter akun kalian, 
➡️ nano accounts.js
🟣Nanti tampilan nya seperti ini : 👇
module.exports = [
  {
    email: "account1@example.com",
    password: "password1"
  },
  {
    email: "account2@example.com",
    password: "password2"
  },
  // Add more accounts as needed
];
📝 ganti dengan Email dan PW akun Teneo kalian,

➡️ KONFIGURASI PROXY : 
🟡 ubah file config.js kalo mau pake proxy dari false ke true , kalo gk ada proxy biarin aja default : 
➡️ nano config.js
🟣Nanti tampilan nya seperti ini : 👇
const useProxy = false; // (set true if want to use proxy, false if not)

module.exports = {
  useProxy
};

➡️ SETUP PROXY :
🟡Masukan proxy kalian ke file proxy.txt 
➡️ nano proxy.tx 
🟣Nanti tampilan nya seperti ini : 👇
ip:port
username:password@ip:port 
http://ip:port http://username:password@ip:port
( Kalian hapus dan ganti dengan proxy kalian, untuk hapus file nya : CTRL + K )

Kalo dah kelar setup semua, tinggal run script
➡️ node index.js
