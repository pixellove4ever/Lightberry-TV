# Lightberry-TV
Système Ambilight pour n'importe quelle source HDMI grâce à un Raspberry Pi

Dans les grandes lignes :
  - La source émettrice diffuse le signal sur le cable HDMI
  - Un Switch HDMI selectionne la source éméttrice (si besoin, cela permet d'appliquer le système "Lightberry" à plusieurs sources comme une console + une box TV + autre par exemple)
    https://www.ezyhd.com.au/product-category/hdmi-switchers/
  - Un Splitter HDMI permet de partager le flux vidéo vers la TV et vers le RPi
    . Entre le Splitter et la TV, il n'y a qu'un câble HDMI 
    . Entre le Splitter et le RPi, d'autres composants viennent s'ajouter
    https://www.ezyhd.com.au/product-category/hdmi-splitters/
  - Donc à la sortie du Splitter, on convertit le signal numérique (HDMI) vers de l'analogique (AV RCA Composite) 
    https://www.zapals.com/mini-hdmi-to-av-converter-hdmi-to-rca-converter-adapter-with-usb-cable.html
  - Une fois le signal converti, on fait l'acquisition du signal avec le RPi grâce à un vidéo Grabber
    https://www.amazon.fr/gp/product/B0013BXFLG
  - Le RPi analyse alors le signal et allume les leds en fonction des couleurs de l'image affichée
  
  Basé sur http://www.instructables.com/id/Ambilight-System-for-Every-Input-Connected-to-Your/
