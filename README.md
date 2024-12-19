----
*  zabbix7-frontend-jpfont.patch 
---
Usage: 
1) install zabbix7-frontend (from ports -> net-mgmt/zabbix7-frontend)
2) install ja-font-ipa-uigothic-00203_5 
3) cp /usr/local/share/fonts/ipa-uigothic/ipagui.ttf /usr/local/www/zabbix7/assets/fonts
    or
   ln -s /usr/local/share/fonts/ipa-uigothic/ipagui.ttf /usr/local/www/zabbix7/assets/fonts
4) /usr/local/www/zabbix7/include
5) patch it.
