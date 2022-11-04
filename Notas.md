# GW RG191
Se trabajará con 915 MHz (Banda US) debido a las carácteristicas del equipo. 
El modelo de la tarjeta  que permite la conexion con LoRa es Semtech SX1301/1275 
Cuenta con 8 canales LoRaWAN con un salida mayor a +27dBm (Cumple con el estandar)
Para la administración de la configuración la información esta protegida ya que tiene certificado TLS y autenticación basada en tokens 
### Turorial para la primera conexión
https://www.youtube.com/watch?v=Q6r6uxqXFCY

## Prerequisitos
Crear una cuenta en: The Things Stack: https://console.cloud.thethings.network/
Encontrar la ip del gateway, se recomienda el uso de nmap: nmap -sn 192.168.200.0/24 (comando utilizado)
Ingresar con la credenciales: **USER: Netsose.01 PASSWORD: Netsose.01**
Descargar el IDE: https://www.st.com/en/development-tools/stm32cubeide.html, para realizar la descarga se debe proporcionar un usuario y un correo electronico al que llegara el enlace de descarga.










## Observaciones
La placa de desarrollo no presenta ningun indicador led ni ningun otro indicador que muestre que el dispositivo se encuentre encendido.
