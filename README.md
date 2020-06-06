# 重新安裝Linux系統

例如想安裝 Ubuntu 18.04 64-bit，並改root密碼為password2020使用

`bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/McDull-GitHub/reset_system/master/install.sh') -u 18.04 -v 64 -a -p password2020`

如果不加 `-p` 會使用默認密碼 `password`

### CentOS 6.9 64-bit：
`bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/McDull-GitHub/reset_system/master/install.sh') -c 6.9 -v 64 -a`

### CentOS 6.9 32-bit：
`bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/McDull-GitHub/reset_system/master/install.sh') -c 6.9 -v 32 -a`

### Debian 8 64-bit：
`bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/McDull-GitHub/reset_system/master/install.sh') -d 8 -v 64 -a`

### Debian 9 64-bit：
`bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/McDull-GitHub/reset_system/master/install.sh') -d 9 -v 64 -a`

### Ubuntu 12.04 64-bit：
`bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/McDull-GitHub/reset_system/master/install.sh') -u 12.04 -v 64 -a`

### Ubuntu 14.04 64-bit：
`bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/McDull-GitHub/reset_system/master/install.sh') -u 14.04 -v 64 -a`

### Ubuntu 16.04 64-bit：
`bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/McDull-GitHub/reset_system/master/install.sh') -u 16.04 -v 64 -a`

### Ubuntu 18.04 64-bit：
`bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/McDull-GitHub/reset_system/master/install.sh') -u 18.04 -v 64 -a`
