digitalsignature
================

Creates a Digital Signature from an XML file

Crea una firma digital, para un archivo xml, lo lee de una ruta en especifico, y lo guarda en otro lugar.
Por favor, para su uso cambie las rutas a las de su ambiente local.

abra el cmd y ubiquese en la ruta del java 

C:\Program Files\Java\jdk1.7.0_40\bin 

ejecute

keytool -genkey -alias mi_cert_ejemplo -keyalg DSA -dname "CN=Usuario, O=Autentia, C=ES" -keypass abc1234 -storepass abc12345 -keystore myKeyStore.jks -validity 365 
