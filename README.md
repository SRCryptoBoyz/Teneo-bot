# Toneo-bot
This script automates network or node operations for Teneo Bot.

##Installation
1. Clone the repository to your local machine:
 git clone https://github.com/recitativonika/teneo-bot.git
2. Navigate to the project directory:
 cd teneo-bot
3. Install the necessary dependencies:
 npm install

##SETUP AKUN :
1. Set up dulu account.js, config.js dan proxy.txt sebelum kalian running script

2. SETUP AKUN/account.js :
   Ubah file account.js untuk mengatur parameter akun kalian
   
modul.ekspor = [
  {
    email: "akun1@example.com",
    kata sandi: "kata sandi1"
  },
  {
    email: "akun2@example.com",
    kata sandi: "kata sandi2"
  },
  // Tambahkan lebih banyak akun sesuai kebutuhan
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

##Run the script:
node index.js
