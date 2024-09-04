# Endpoint-Detection-and-Response
EDR ürünü hakkında makale
                                EDR(Endpoint Detection and Resonse)
EDR (Uç Nokta Algılama ve Yanıt) çözümleri, merkez ağa bağlı bilgisayarlar, cep
telefonları, IoT cihazları gibi uç nokta cihazlarının güvenliğini anlık olarak takip
etmek ve uç nokta cihazlarının bilgi ve veri güvenliğini artırmak için geliştirilen
araçlardır. Bu cihazlar, anlık olarak veri toplayarak anomali algılama, uyarı
oluşturma ve kayıt tutma görevlerini üstlenir. EDR çözümleri tarafından toplanan
veriler, veri tabanlarında saklanabilir ve SIEM ürünlerine gönderilip SIEM ürünleri
tarafından kullanılabilir

![image](https://github.com/user-attachments/assets/662a9f38-7d4d-4bf2-9d1e-b87bb6464d50)

Peki, nedir bu uç nokta cihazları?

Uç nokta cihazları, merkez ağa bağlı bilgisayarlar, telefonlar, tabletler ve IoT
cihazlarını kapsar. Uç nokta cihazları, kaleye doğrudan bağlı çevre köyler olarak
düşünülebilir. Kaleyi fethetmek isteyen düşman askerler, kaleye yolu olan bir köyü
fethederse, kaleye ulaşabilmek için kolay bir edinmiş olurlar. Kaleyi savunmak
askerlerin görevidir. Cihazlarımızı savunmak için de çeşitli askerlerimiz vardır; bu
askerler antivirüsler veya EDR çözümleri gibi ürünlerdir. Antivirüs ürünleri bilinen
virüslerin, solucanların, casus yazılımların ve diğer kötü amaçlı yazılımları
veritabanında bulundurur ve yenileri keşfedildiğinde bu veritabanı güncellenir. Eğer
cihaz taraması sırasında bu veritabanında bulunan bir anomaliye denk gelinirse,
anomaliyi karantina altına alıp kullanıcıya bildirebilir veya silebilir. Ancak antivirüs
veritabanı güncel değilse veya henüz keşfedilmemiş bir anomali söz konusuysa, tam
bu noktada EDR çözümleri devreye giriyor. Ücretsiz olarak Windows Office
uygulamaları kullanmak istedik, o çok sevdiğimiz oyun çok pahalı ve ücretsiz olarak
indirip oynamak istedik veya o okumak için heyecanlandığımız o kitabın PDF
dosyasını bulduk ve indirdik. Antivirüsümüz bize herhangi bir uyarı vermedi veya
indirdiğimiz dosyayı silmedi, şimdi gönül rahatlığıyla bu indirdiğimiz dosyayı
kullanabiliriz. Word dosyasını açtığımızda her şey olması gerektiği gibi orijinaliyle
birebir aynı görünüp ve aynı işlevleri hatta lisanslı olduğu için antivirüsümüze bile
yakalanmadı ancak görmediğimiz tarafta uygulamanın cihazımızla iletişime geçtiği
kısımda hangi komutları ilettiğini statik olarak göremeyiz. Bu işlemi bizim için EDR
çözümleri gerçekleştirir.

Peki, EDR çözümleri nelerdir?

EDR çözümleri birer yazılımdır. Farklı üreticiler tarafından yapılan arayüzü olan
uygulamalardır. Başlıca üretici / dağıtıcıları Crowdstrike Falcon Endpoint Protection,
McAfee Endpoint Security olarak gösterilebilir. Her EDR çözümü her alanda güvenlik
sağlamaz; farklı çözümlerin farklı alanları olabilir. Örneğin, bazı EDR çözümleri
kullanıcı hesap etkinlikleri alanında etki sağlayamazken, bazıları sağlayabilir. EDR
çözümlerinin kurulumu bakımından ikiye ayrılır: EDR agent ve EDR agentless. EDR
agent, uç cihaza agent yükleyerek çalışırken, EDR agentless uç noktaya agent
yüklemeden çalışır. EDR çözümleri çalışma modu bakımından Admin (cihaz
kernel’inde) ve Normal kullanıcı olarak ikiye ayrılır. Kernel'da çalışan EDR çözümleri,
daha derin görünürlük, daha güçlü koruma ve daha az sistem yükü avantajlarını
sağlar ancak daha karmaşık kurulum, daha fazla güvenilirlik riski (işletim sisteminin
kritik bir parçası olan çekirdeğe erişim iznine sahip olmasından dolayı EDR’ın ele
geçirilmesi tüm sistemde risk oluşturur) ve daha az uyumluluk (bazı işletim sistemleri
çekirdek erişimine izin vermez) gibi dezavantajlara sahip olabilirler. Ek olarak, EDR
yazılımları SIEM ürünleriyle bağlanabilir ve yapılan veri analizleri kullanılmak üzere
SIEM ürünlerine gönderilebilir.

EDR çözümleri nasıl çalışır?

EDR yazılımı, işletim sisteminden, dosyalardan, kayıt defterinden, ağ trafiğinden
sürekli veri toplar ve bu verileri anomali bulmak için analiz eder. EDR verileri hem
gerçek zamanlı hem de geçmişe dönük olarak toplayabilir. Yani, geçmişe dönükte
anomali algılanabilir. Analizler istatistiksel modeller, makine öğrenimi algoritmaları ve
davranışsal analiz gibi çeşitli teknikler kullanarak gerçekleştirilir. Anomali tespit
edildiğinde güvenlik ekiplerine uyarı gönderilir. EDR yazılımları güvenlik ekiplerine
tehditleri araştırma ve bunlara

Metehan
