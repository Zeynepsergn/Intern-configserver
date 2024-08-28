# Config-Server
------------------

Uygulamalara ait olan konfigürasyonların rest-apiden url ile alınabilmesini sağlar.

# Özellikler
-------------------

Uygulamalara ait konfigürasyonlar resources/config altında yer almaktadır.

# Erişim
----------------------

http://localhost:8088/ adresi altında dosyalara eişim configde yer alan bilgiler ile erişilir. Örneğin; 

<pre>
http://localhost:8088/spos-service.yml
http://localhost:8088/borc-service.yml
http://localhost:8088/odeme-service.yml
</pre>

şeklinde erişilir.