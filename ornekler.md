-Çok ayrıntılı bir açıklama arıyorsanız komutun manuel sayfasına bakın. herşeyide yazamayız. ileride man sayfalarını türkçeye çevirebiliriz. yardım ederseniz çok mutlu olurum :).

#$ pwd
* Bulunduğunuz dizinin ismini ekrana yazdırır.

#$ ls
* Bulunduğunuz dizindeki dosya isimlerini yazdırır.
* (-a) bütün dosya türlerini görmenizi sağlar.
* (-l) dosyaların yetkileri ile sıralanmasını sağlar.

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
