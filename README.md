# nginx cross
It is nginx fork with applied cross-compilation patch based on [this](https://github.com/chewi/cross-boss/blob/master/root/etc/portage/patches/www-servers/nginx/nginx-cross.patch).  
Some configurations are already created: i686, amd64, arm.    
**Usage**: ./configure --crossbuild=Linux:arm --crossbuild-config="cross/arm.config"
