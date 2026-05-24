# tools

<h4>Linux Commands:</h4>
<p>
Generate SSH Key: ssh-keygen
</p>
<hr>


<h4>Installaion steps of valet Linux Plus</h4>
<p>
<b>Step 1</b>

```
sudo apt-get install curl libnss3-tools jq xsel openssl ca-certificates
```
</p>

<p>
<b>Step 2</b>
  
```
sudo add-apt-repository ppa:ondrej/php
```
</p>

<p>
<b>Step 3</b>

```
sudo apt-get install php*-cli php*-curl php*-mbstring php*-xml php*-zip php*-posix php*-mcrypt php*-sqlite3 php*-mysql php*-pgsql
```
</p>

<p>
<b>Step 4</b>
Add composer & node js
</p>

<p>
<b>Step 5</b>

```
composer global require genesisweb/valet-linux-plus
```
</p>

<p>
<b>Step 6</b>
add `export PATH="$PATH:$HOME/.config/composer/vendor/bin"` to `~/.bashrc`
</p>

<p>
<b>Step 7</b>

```
valet install
```
</p>

<p>
<b>step 8</b>

```
sudo mysql -u root
```
</p>

<p>
<b>step 9</b>

```
ALTER USER 'valet'@'localhost' IDENTIFIED WITH caching_sha2_password BY 'YourStrongPassword';
```

or

```
CREATE USER 'valet'@'localhost' IDENTIFIED WITH caching_sha2_password BY 'YourStrongPassword';
```
</p>

<p>
<b>step 10</b>

```
GRANT ALL PRIVILEGES ON *.* TO 'valet'@'localhost' WITH GRANT OPTION;
```
</p>

<p>
<b>step 11</b>

```
FLUSH PRIVILEGES;
```
</p>

<p>
<b>step 12</b>

```
EXIT;
```
</p>

<p>
<b>step 13</b>

```
composer create-project phpmyadmin/phpmyadmin
```
</p>
