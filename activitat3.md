# Activitat 3

**3.1.-** Llista els Virtual Hosts d'Apache per tal de veure si owncloud.XYZ.com està habilitat amb la comanda:

`apache2ctl -S`

![Captura](activitat3-1.png)

**3.2.-** A Owncloud podem veure que hi ha una serie de carpetes per defecte, mostra la ruta real a les tres carpetes dins de la teva MV.

`/var/www/html/owncloud/data/(username)/files`

**3.3.-** Al directori **Learn more about owncloud** hi ha informació en forma de fitxers pdf. Consulta'ls i respon aquestes preguntes:

* Quin són els tres tipus de protecció de dades que ofereix Owncloud?
1- **Encriptacio en repos** 
2- **Encriptació en trànsit** 
3- **Xifratge d'extrem a extrem** 

* Fes una petita descripció de cada un d'ells.
1- Encriptacio en repos significa cifrar tots els arxius
guardads desde el servidor de aplicacions ownCloud
avans de guardarlos al almacenament real.

2- ownCloud utilitza un xifratge de clau mestra
mètode per a això que és compatible amb tots els fitxers
sistemes. Per a l'emmagatzematge d'objectes S3, el natiu
Es recomana un mecanisme de xifratge S3.
El xifratge de la clau mestra evita que els fitxers siguin
llegir des de l'emmagatzematge.

3- Per tal d'assegurar realment que ni el
administradors del sistema ni ningú més
la vostra organització pot accedir encriptada
El xifratge d'extrem a extrem només de dades és viable
solució.

* Per quina raó ens recomana utilitzar Owncloud per als documents de Microsoft Office de la nostra empresa?
**Microsoft Office ha estat durant molt de temps
estàndard de facto en suites de productivitat d'oficina
i aquesta influència s'ha col·locat en altres
aspectes del mercat del programari laboral.
Moltes empreses insisteixen a utilitzar Microsoft
Oficina, cosa que la converteix en un requisit per als seus
contactes comercials. Encara que n'hi ha de bones
alternatives, moltes organitzacions no
considerar el canvi: inversions en llicències
A més a més molts temen
inconvenients per incompatibilitats.**

* Això passa a tots els països?

* Quina és la llicència d'OWncloud Enterprise?
 **La llicencia és "ownCloud Commercial License"**
* I la d'Owncloud Standard?
 **La llicencia és "AGPLv3"**
* Es poden veure videos en Streaming directament des de Owncloud?
**Sí, es podem veure videos en streaming tant en la llicencia de Enterprise com la Standard**
* Es poden connectar directoris de Google Drive a Owncloud?
**Sí, es poden connectar directoris de Google Dirve a Owncloud**
* I Dropbox?
**També es pot fer**
* Compta Owncloud amb antivirus? En cas afirmatiu com es diu?
**No el te integrat, pero es pot instal·lar apart**


**3.4.-** Mostra els següents canvis de paràmetres d'usuari:

* Posa't una imatge d'usuari.
* Afegeix el teu mail de l'Institut.
* Canvia l'idioma a català.
![Captura](activitat3-2.png)
* Mostra la versió d'Owncloud instal·lada.
![Captura](activitat3-5.png)
