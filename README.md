# fonts-for-google-colab

## on Google Colab

Install Noto_Sans_SC:

```
!rm Noto_Sans_SC.zip
!wget https://github.com/nodewee/fonts-for-google-colab/raw/main/fonts/Noto_Sans_SC.zip
!mkdir /usr/share/fonts/myfonts
!unzip /content/Noto_Sans_SC.zip -d /usr/share/fonts/myfonts/Noto_Sans_SC/
!fc-cache -f -v
# display / check
!fc-list | grep Noto
```

Usage:

Font name: `NotoSansSC-Regular`, `NotoSansSC-Bold`