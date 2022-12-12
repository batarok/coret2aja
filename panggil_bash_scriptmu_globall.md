Jika memiliki bash skrip (file .sh) di LINUX dan ingin di panggil secara global apakah bisa? Tentu bisa
contoh file .sh nya ada di /home/user/folderfile/file.sh

caranya kamu harus ada di root directory dulu (/home/user) setelah itu edit file .bashrc
edit file .bashrc tidak perlu menggunakan sudo, karena yg bisa akses cuma user mu aja
edit file .bashrc > nano .bashrc atau bisa juga vi .bashrc
setelah itu scrool sampai bawah, lalu beri tanda dimana letak skripmu
misal #ini buat manggil skrip bash global
lalu dibawah nya tuliskan perintah
export PATH="$PATH:/home/user/folderfile/"

Cukup seperti itu untuk memanggil bash script mu secara global
