# BOZ213d01a02
Python, IDLE ve GitHub Lisansları

1. IDLE neden normal bir kısayolla çalıştırılamaz? Kendisi nerede bulunur?

IDLE’ın bağımsız bir idle.exe dosyası yoktur. Python içerisinde bulunan idlelib paketi üzerinden çalışır.

IDLE dosyaları genellikle şu klasörde bulunur:

Python\Lib\idlelib

IDLE, arka planda Python kullanılarak çalıştırılır:

pythonw.exe -m idlelib

Bu nedenle IDLE, Python’dan tamamen bağımsız bir program değildir.

⸻

2. Python dosya sistemi nasıl biçimlenmiştir?

Python kurulunca temel olarak şu dosya ve klasörler bulunur:

* python.exe: Python kodlarını çalıştırır.
* Lib: Python’un standart kütüphanelerini içerir.
* site-packages: Sonradan yüklenen paketlerin bulunduğu klasördür.
* Scripts: pip gibi yardımcı araçları içerir.
* .py: Python kaynak kodu dosyalarının uzantısıdır.

Örnek bir Python projesinin dosya yapısı:

proje/
├── main.py
├── README.md
└── LICENSE

* main.py: Programın Python kodlarını içerir.
* README.md: Proje hakkında açıklama içerir.
* LICENSE: Projenin kullanım koşullarını belirtir.

⸻

3. GitHub lisans sözleşmeleri nelerdir ve neden kullanılır?

Lisans, bir yazılımın başkaları tarafından nasıl kullanılabileceğini, değiştirilebileceğini ve dağıtılabileceğini belirler.

Lisans	Özelliği	Neden Kullanılır?
MIT	Az kısıtlayıcıdır. Kod kullanılabilir ve değiştirilebilir.	Basit ve açık kaynak projelerde kullanılır.
GPL	Değiştirilen ve dağıtılan türev yazılımların da açık kaynak olmasını amaçlar.	Açık kaynak yapısını korumak için kullanılır.
Apache 2.0	Kullanım ve değiştirmeye izin verir, ayrıca patent hükümleri içerir.	Büyük ve profesyonel projelerde tercih edilir.
BSD	MIT’e benzer, az kısıtlayıcıdır.	Akademik ve açık kaynak projelerde kullanılır.

Neden MIT lisansı tercih edilebilir?

MIT lisansı basit, anlaşılır ve fazla kısıtlayıcı değildir. Kullanıcıların kodu kullanmasına, değiştirmesine ve dağıtmasına izin verdiği için küçük Python projelerinde sık tercih edilir. 
