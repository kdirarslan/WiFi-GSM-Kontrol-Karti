## WiFi-GSM Kontrol Kartı
```
Version:    v1.3
Tarih  :    12.02.2019
KiCad ile Tasarlanmıştır.
```

WiFi-GSM, ESP8266, SIM800C, buzzer ve iki adet röle barındıran tümleşik bir kontrol kartıdır. 
Dahili 3A regülatör ile kartın gerekli güç bağlantısı sağlanır.

İhtiyaca göre ESP8266 WiFi özelliği kullanılabilir, Web sunucusu üzerinden dinamik ayarlar yapılabilir. 
Bir ağa bağlanarak İnternet üzerinden kontrol sağlanabilir.

İhtiyaca göre GSM ile uzaktan kontrol sağlanabilir ve sensör verileri alınabilir. 

Şebekeye bağlanma, arama ve SMS gönderme durumlarında yüksek akım çeken SIM800C modülünün güç gereksinimi karşılamak için güçlü bir besleme hattı oluşturulmuştur. 

Kart üzerindeki ESP8266, SIM800C, röleler ve buzzer için 12V 1A adaptör kullanmak yeterlidir. 
 

**Ön görünüm**

![3D Üst Karşı Görünüm](https://user-images.githubusercontent.com/58399702/188584779-7e095e8d-b989-4520-b9cd-b86f2820adc2.jpg)

**Arka Görünüm**

![3D Arka Görünüm](https://user-images.githubusercontent.com/58399702/188585505-8005308d-7f68-499c-9c23-5145a9c2ceda.jpg)

**PCB Layout Görünümü**

![PCB Görünümü](https://user-images.githubusercontent.com/58399702/188584254-263756a2-7a3b-4bae-b3ab-3c9e8cfd3e0c.jpg)


## Kart Özellikleri

### Donanım Özellikleri
- ESP8266
- SIM800C
- 2 Röle
- 1 Buzzer
- 1 Digital Input
- 1 Analog Input
- Mikro SIM kart konnektörü
- Dahili mikrofon
- Hoparlör bağlantı konnektörü
- 3dBi 90C SMA Anten
- Dahili 3A voltaj regülatörü
- SIM kart konnektöründe TVS koruması
- Besleme hattında ters polarite koruması

### Tasarım ve Kutu Özellikleri
- Kart 97mmx85mm (EnxBoy) boyutlarında özel kutuya yerleşecek şekilde tasarlanmıştır.
- Kutu üzerinde hem pano hem de duvar montaj aparatı mevcuttur.


**Soldaki alt kapak: opsiyonel olarak pano rayına ve duvara montaj kulakçıkları mevcuttur**

![ArduGSM Kutu](https://user-images.githubusercontent.com/58399702/171063530-c1530e02-cee1-432a-b798-4fea779e2fbf.jpg) 


**Kutu - Montajlı**

![Kutu kutu montajlı](https://user-images.githubusercontent.com/58399702/171063774-f5ca42cf-f03c-4323-a74d-35c914cc97f1.jpg)
------------------------

