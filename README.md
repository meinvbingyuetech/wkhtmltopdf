- 不能用centos8 , 用7的版本
------------------------------------------------------------------------------------------------------------------------------------
```
wget https://github.com/wkhtmltopdf/packaging/releases/download/0.12.6-1/wkhtmltox-0.12.6-1.centos7.x86_64.rpm

yum install fontconfig freetype libpng libjpeg libX11 libXext libXrender xorg-x11-fonts-Type1 xorg-x11-fonts-75dpi

rpm -ivh wkhtmltox-0.12.6-1.centos7.x86_64.rpm

将中文字体上传到这里：
cd /usr/share/fonts

wkhtmltopdf https://kbc.bestbluefield.com/upload/delivery_notice/1/KWT23071009.html 1.pdf
```
------------------------------------------------------------------------------------------------------------------------------------
```
fc-list: 列出系统中安装的font
fc-cache -f -v: 刷新字font缓存
```
