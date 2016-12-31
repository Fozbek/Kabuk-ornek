#$ pwd
* Bulunduğunuz dizinin ismini ekrana yazdırır.

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
* 


















#$ touch /home/dizin1/dizin2/dosya.sh
* Yeni bir dosya yaratmanızı sağlar manuel sayfasından klasorlere dosyalara vereceğiniz özellikleri ayarlayabilirsiniz 

#$ mkdir
* Bu komutla klasör yaratabilirsiniz ve yine man sayfasından nasıl detaylı kullanıcağınıza bakabilirsiniz.

#$ rm
* İşte çok tehlikeli bir komut **sudo rm -rf /** şeklinde yazıldığında tüm dosyalarınız gider şaka değil sistem bile gider format atmak zorunda kalırsınız :D
* bu komut dosya silmek için birebir ama dikkatli kullanın lütfen.

#$ rmdir
* Bu yukarıdakiyle aynı fakat bununla dizin siliyoruz.

#$ cat
* bununla dosyanın içinde yazan ilgileri komut satırına çıkarıyoruz. hızlı bir göz atma için çok ideal bir komut.

#$ cp copyalanacak-belge kopyalanacak-konum
* bununla dosyalarınızı kopyalayabilirsiniz 

#$ mv taşınacak-belge gideceği-konum
* bu komut ile dosya taşıyabiliyoruz

#$ grep
* Bu komut ile dosyalarda sözcük vs. arayabiliyoruz çok kullanışlı bir komut

#$ chmod
* Bu komut ile dosyaaların yetkisini değiştirebiliyoruz işte bu harika. bir şey ama bir o kadarda korkunç bir komut tek bir komutla sisteminizi mahvedebilirsiniz.

#$ echo
* Bu komut çok güzel örneğin bir dosyadaki belli kelimeleri başka bir dosyaya yazdırabiliyorz. diğer komutlarla iç içe kullanılabildiği için harika bir komut. daha sonra çok detaylı anlatıcağım.

#$ cd
* Bu komut ile dosyadan dosyaya atlayabilirsiniz. yane kısacası dosya değiştirmenizi sağlıyor.

#$ curl
* Bu komut internetten bilgi çekmeye yarıyor buda çok güzel bir komut.
