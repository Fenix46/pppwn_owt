# PPPwn_ow
Una adaptación del código de stooged para que funcione con PPPwn_cpp

Esto sirve para que arranque en un modem que tenga un sistema OpenWrt instalado

- Se requiere Putty para acceder al sistema del modem
- Necesitas descargar los payload y tener los stage1.bin y stage2.bin para el FW correspondiente
- la instalación es sencilla simplemente copia run.sh, pppwn, stage1.bin y stage2.bin a /root dentro del modem
- usa los comandos de install.sh para modifical el /etc/rc.local
- reinicia el modem

Lo probado con GL-MT300N-V2

https://github.com/stooged/PI-Pwn
https://github.com/xfangfang/PPPwn_cpp?tab=readme-ov-file
