# OTA- ESP826-Espota-Standalone
  
Version of the tool in standalone mode for Windows. Unzip the archive into a directory. Then start the espota.exe file with the same arguments.
Examples:
For the file spiffs.bin
     espota.exe ota -i 192.168.1.20 -s -f C:\Users\CHRIST~1\AppData\Local\Temp\arduino_build_643706/esp8266_web_Alexa.spiffs.bin --auth=admin -r

 Authenticating...OK
 Uploading: [============================================================]

100% Done...
For the program file ino.bin

    espota.exe ota -i 192.168.1.20 -f C:\Users\CHRIST~1\AppData\Local\Temp\arduino_build_643706/esp8266_web_Alexa.ino.bin --auth=admin -r
    
Version de l'outil en mode autonome pour Windows.
Décompressez l'archive dans un répertoire. Puis lancer le fichier espota.exe avec les même arguments.
Exemples:
Pour le fichier spiffs.bin

     espota.exe ota -i 192.168.1.20 -s -f C:\Users\CHRIST~1\AppData\Local\Temp\arduino_build_643706/esp8266_web_Alexa.spiffs.bin --auth=admin -r

 Authenticating...OK
 Uploading: [============================================================]
 100% Done...

Pour le fichier programme ino.bin.

    espota.exe ota -i 192.168.1.20 -f C:\Users\CHRIST~1\AppData\Local\Temp\arduino_build_643706/esp8266_web_Alexa.ino.bin --auth=admin -r

