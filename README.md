Canlı TV kanal listesi
Monitördeki Canlı TV uygulaması her açılışta bu depodaki kanallar.json dosyasını okur. Bir kanal çalışmazsa uygulamayı yeniden kurmanıza gerek yok; bu dosyayı düzeltmeniz yeterli.

Bir kanalı düzeltmek
github.com'da bu depoyu açın → kanallar.json → sağ üstteki kalem (✏️ Edit) simgesi.
İlgili kanalın satırında değişikliği yapın:
Yayın adresi değiştiyse: "yayinlar": [ ... ] içindeki adresi yenisiyle değiştirin.
Kanal artık sadece sitesinden açılsın istiyorsanız: "yayinlar": [] yapın.
Kanalın sitesi değiştiyse: "resmiSayfa" adresini güncelleyin.
Aşağıdaki yeşil Commit changes düğmesine basın.
Monitörde Canlı TV'yi kapatıp açın (GitHub'ın değişikliği yayması birkaç dakika sürebilir).
Kurallar
Adresler https:// ile başlamalı.
grup yalnızca "dizi" veya "haber" olabilir.
Virgül ve tırnak işaretlerine dikkat edin. Dosya bozulursa uygulama son çalışan listeyi kullanmaya devam eder; ekran boş kalmaz.
Yalnızca kanalların kendi sitelerinde yayınladığı ücretsiz yayın adreslerini kullanın.****
