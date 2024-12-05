Teneo-bot MULTY AKUN
This script automates network or node operations for Teneo Bot.

#Installation
1. Clone the repository to your local machine:
 git clone https://github.com/recitativonika/teneo-bot.git
2. Navigate to the project directory:
 cd teneo-bot
3. Install the necessary dependencies:
 npm install

#SETUP AKUN :
1. Set up dulu account.js, config.js dan proxy.txt sebelum kalian running script

2. SETUP AKUN/account.js :
   Ubah file account.js untuk mengatur parameter akun kalian
   
GNU nano 8.2                  account.js
module.exports = [
  {
    email: "isi dengan email/ your email",
    password: "isi dengan password / your password"
  },
  {
    email: "email",
    password: "password"
  },
{
    email: "email",
    password: "password"
  {
    email: "email",
    password: "password"
  },
  // tambahkan  akun lain jika ada / Add more accounts as needed
];
3. KONFIGURASI PROXY : 
 ubah file config.js kalo mau pake proxy ke true , kalo gk ada proxy biarin aja default   ("false" menggunakan proxy)
const useProxy = false; // (set true if want to use proxy, false if not)

module.exports = {
  useProxy
};

4. SETUP PROXY 
ubah file proxy.txt dengan proxy yang sesuai di bawah ini,
ip:port
username:password@ip:port
http://ip:port
http://username:password@ip:port

#Run the script:
node index.js
