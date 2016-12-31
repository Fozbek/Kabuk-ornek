
#$ ls
* Kullandığınız seçeneklere göre dosyaları listeler.
* -a, --all
 * '.' ile başlayan dosyaları reddetme.
* --author
 * -l ile kullanıldığında dosyaları oluşturan kişiyi gösterir.
* -b, --escape
 * Boşlukları kaçış karakterleri ile göster
* -B, --ignore-backups
 * '~' ile biten dosyaları listelemez.
* -c
 * -lt ile kullanıldığında dosyaların son değiştirlme tarihine göe sıralar
 * -l ile kullanıldığında değiştirilme tarihini gösterir ve isime göre sıralar
* -C
 * Kolonlara göre sıralar.
* --color[=WHEN]
 * Çıktıyı renklendirir. Seçeneksiz kullanıldığında daha çok özelliğini görebilirsiniz
* -d , --directory
 * Klasörlerin sadece kendilerini göster. İçeriği gösterme.
* -D, --dired
 * Emacs dired mode için dizayn edilmiş liste çıkar
* -f
 * Sıralama  , -aU ile kullan , -ls --color kullanma.
* -F, --classify
 * Bir dosyanın  klasör ve normal dosya oluşuna göre sınıflandırr.
* --file-type
 * Aynı şekilde , ama * ekleme
* --format=WORD
 * -x çapraz , -m virgül , -x yatay , -l uzun , -1 tek kolon , -l ayrıntılı , -C dikey
* --full-time 
 * -l --time-style=full-iso ile aynı özellikter. tüm zaman etiketlerini ayrıntılı bir şekilde gösterir.
* -g
 * -l gibi ama dosya sahibini göstermez.
* --group-directories-first
 * Dosyalardan önce dizinleri listele:
 * --sort ile kullanılabilir, fakat --sort=none (-U) gruplamayı iptal eder.
* -G, --no-group
 * Uzun listelerde grup ismini yazmaz.
* -h, --human-readable
 * -l veya -s ile kullanıldığında insanın okuyabilecceği formatta göster. (örn: 234K 12M 3G)
* --si
 * 1024 katları yerine 1000 katlarını kullan.
* -H, --dereference-comman-line
 * Komut satırında listelenen sembolik bağlantıları izleyin
* --dereference-command-line-symlink-to-dir
 * Her komut satırının sembolik bağlantısını takip et
 * Bu bir klasörü işaret ediyor.
* --hide=PATTERN
 * shell düzeni ile eşleşen komuta göre çıktıyı listeleme.( -a ve -A geçersiz kılar)
* --indicator-style=WORD
 * dosyalara WORD yerine yazılan koda göre ayraç ekler: none (default) , slash (-p) , file-type (--file-type) , classify(-F)
* -i , --inode
 * her dosyanın index numarasını yazdır.
* -I , --ignore=PATTERN
 * PATTERN ile eşleşen çıktıları listeleme.
* -k, --kibibytes
 * 1024-byte varsayılan disk kullanımı
* -l
 * Uzun liste formatını kullan
* -L , --dereference
 * Sembolik bir bağlantı için dosya bilgileri gösterilirken, bağlantı için değil bağlantı başvurduğu dosyanın bilgilerini gösterin
* -m
 * Boşluklar yerine virgüller ile doldur.
* -n, --numeric-uid-gid
 * -l gibi fakat kullanıcı ve grup id listeler
* -N, --literal
 * Çıktı isimlerini yineleme.
* -o
 * -l gibi fakat grup bilgisini listeleme
* -p , --indicator-style==slash
 * çıktıların sonuna '/' ekler
* -q , --hide-control-chars
 * grafik olmayan karakterler yerine '?' yaz.
* --show-control-chars
 * grafik olmayan karakterleri yazdır ( varsayılan olarak 'ls' komutu ile gelen biçim)
* -Q , --quote-name
 * Giriş adlarını tırnak işareti içine alın.
