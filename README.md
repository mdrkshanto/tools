# tools

<h4>Linux Commands:</h4>
<p>
Generate SSH Key: ssh-keygen
</p>
<hr>


<h4>Installaion steps of valet Linux Plus</h4>
<p>
step 1
``
  sudo apt-get install curl libnss3-tools jq xsel openssl ca-certificates
``
</p>
# step 2
sudo add-apt-repository ppa:ondrej/php

# step 3
sudo apt-get install php*-cli php*-curl php*-mbstring php*-xml php*-zip php*-posix php*-mcrypt php*-sqlite3 php*-mysql php*-pgsql

# step 4
Add composer & node js

# step 5
composer global require genesisweb/valet-linux-plus

# step 6
add `export PATH="$PATH:$HOME/.config/composer/vendor/bin"` to `~/.bashrc`

# step 7
valet install

# step 8
composer create-project phpmyadmin/phpmyadmin
