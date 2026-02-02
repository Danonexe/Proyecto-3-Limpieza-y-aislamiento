# Instalación Mínimos Privilegios

# Windows

## Instalación SO

Hemos elegido Windows 10 Pro porque es la versión que mejor equilibra control, seguridad y estabilidad para crear una instalación mínima y endurecida, especialmente en un entorno de navegación web y ofimática básica.  
<img width="671" height="504" alt="image" src="https://github.com/user-attachments/assets/ca7cd8ad-cc47-43cb-bca7-b3b2d2852dea" />

Vamos a ir paso a paso para la instalación de mínimos privilegios, durante la instalación:

* Usa cuenta local, no Microsoft  
* No conectes a Internet hasta terminar (evita apps automáticas)

<img width="673" height="444" alt="image" src="https://github.com/user-attachments/assets/21659f9e-78f6-4d88-819b-b50e26dae863" />


* Idioma y región correctos  
* No actives Cortana

<img width="674" height="422" alt="image" src="https://github.com/user-attachments/assets/ba3dfd4a-4936-4c59-83cb-873256004074" />


* Desmarca todo lo de “experiencia personalizada”, anuncios, diagnóstico opcional, etc.

## Eliminación de aplicaciones innecesarias (bloatware)

Durante la instalación estándar de Windows 10 se incluyen numerosas aplicaciones orientadas a ocio, consumo de contenidos o integración con servicios en la nube, que no son necesarias para un equipo destinado exclusivamente a navegación web y ofimática básica.

Las aplicaciones que hemos visto innecesarias son las siguientes:  
Xbox (Game Bar, Xbox Services)

* Cortana  
* OneDrive (si no se usa)  
* Clipchamp  
* Teams personal  
* Noticias  
* Clima  
* Mapas  
* Skype  
* Spotify (si viene preinstalado)  
* Paint 3D  
* Mixed Reality Portal

No aportan funcionalidad para navegación u ofimática y aumentan superficie de ataque y consumo de recursos.

<img width="671" height="478" alt="image" src="https://github.com/user-attachments/assets/454f2535-f162-4d82-99ff-75116fcc8e67" />


## Servicios de Windows

Un servicio de Windows es un proceso que se ejecuta en segundo plano y que proporciona una funcionalidad específica al sistema operativo. Muchos servicios están pensados para situaciones concretas (juegos, impresión, dispositivos externos, asistencia remota, etc.) y no son necesarios para un equipo destinado únicamente a navegación web y ofimática básica.

Los servicios que hemos visto innecesarios son los siguientes:

* Xbox Services  
* Windows Search  
* Print Spooler (si no hay impresora)  
* Fax  
* Remote Registry  
* Bluetooth Support Service (si no se usa)  
* Windows Error Reporting  
* Touch Keyboard (si no es táctil)


<img width="672" height="503" alt="image" src="https://github.com/user-attachments/assets/7b803a7d-ee5d-47ff-8323-67bf3bf131ea" />


## Protocolos y funciones de Windows

Windows incluye protocolos de red y características opcionales pensadas para garantizar compatibilidad con sistemas antiguos o usos muy concretos. Sin embargo, muchas de estas funciones no son necesarias en un equipo destinado a navegación web y ofimática básica y pueden suponer un riesgo de seguridad si permanecen activas.

* SMB 1.0  
* Internet Explorer 11  
* Windows Media Player  
* XPS Services  
* Work Folders Client  
* Remote Differential Compression

<img width="673" height="507" alt="image" src="https://github.com/user-attachments/assets/5406ba2b-401c-43ff-b048-2338df862dcf" />


## Configuración de uso compartido de red

La configuración de uso compartido de Windows define cómo se comporta el equipo dentro de una red, es decir, qué información comparte, qué servicios ofrece y qué tan visible es para otros dispositivos.

En un sistema destinado a navegación web y ofimática básica, no es necesario que el equipo sea visible ni que comparta recursos en la red.

<img width="672" height="507" alt="image" src="https://github.com/user-attachments/assets/10dda7d4-c384-49f1-a112-1513159d8c9a" />


## Navegación web segura

Instalar solo Firefox o Chrome con las siguientes extensiones: uBlock Origin, HTTPS Everywhere, Bitwarden (opcional)

Y configurar: Bloqueo de cookies de terceros y DNS seguro (Cloudflare o Quad9)
