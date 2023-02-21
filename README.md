# Instalar-servidor-VPN-(OpenVPN)
Instalar **OpenVPN** en Ubuntu, Debian, AlmaLinux, Rocky Linux, CentOS y Fedora en 2 minutos.

Al ejecutar este script instalará tu propio servidor VPN en menos de 2 min, sin  importar si no haz usado openVPN anteriormente y si no tienes mucha experiencia. Te indicaremos como hacerlo.

# Instalación

Ejecuta el script y sigue las instrucciones: 

```
wget https://bit.ly/install-vpn-openvpn -O openvpn-install.sh && bash openvpn-install.sh
```

<p align="center">
  <img width="300" src="https://i.imgur.com/CV0474V.png">
</p>

Al finalizar la instalación te dejara en el directorio ```/root``` un archivo del usuario tipo  ```xxx.ovpn``` que es el archivo que tienes que enviar por mail para configurar la aplicación cliente ```OpenVPN```.

<p align="center">
  <img width="300" src="https://i.imgur.com/lTA4Sk0.png">
</p>

Luego puedes correr de nuevo el script para añadir más usuarios, borrar alguno de ellos o para desinstalar el server por completo.

<p align="center">
  <img width="300" src="https://i.imgur.com/szgofzy.png">
</p>

