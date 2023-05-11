# fonts-for-google-colab

## on Google Colab

Install Noto_Sans_SC:

```
!wget https://github.com/nodewee/fonts-for-google-colab/blob/main/fonts/Noto_Sans_SC.zip
!mkdir /usr/share/fonts/myfonts
!unzip Noto_Sans_SC.zip -d /usr/share/fonts/myfonts/Noto_Sans_SC/
!fc-cache -f -v
# display / check
!fc-list | grep Noto
```
