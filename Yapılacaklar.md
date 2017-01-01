
#$ pwd
* Bulunduğunuz dizini çıktı olarak verir.

#$ touch /home/dizin1/dizin2/dosya.sh
* Yeni bir dosya yaratmanızı sağlar manuel sayfasından klasorlere dosyalara vereceğiniz özellikleri ayarlayabilirsiniz 

#$ mkdir
* Bu komutla klasör yaratabilirsiniz ve yine man sayfasından nasıl detaylı kullanıcağınıza bakabilirsiniz.

#$ rm
* İşte çok tehlikeli bir komut **sudo rm -rf /** şeklinde yazıldığında tüm dosyalarınız gider şaka değil sistem bile gider format atmak zorunda kalırsınız :D
* Bu komut dosya silmek için birebir ama dikkatli kullanın lütfen.

#$ rmdir
* Bu yukarıdakiyle aynı fakat bununla dizin siliyoruz.

#$ cat
* Bununla dosyanın içinde yazan ilgileri komut satırına çıkarıyoruz. Hızlı bir göz atma için çok ideal bir komut.

#$ cp copyalanacak-belge kopyalanacak-konum
* Bu komut ile dosyalarınızı kopyalayabilirsiniz.

#$ mv taşınacak-belge gideceği-konum
* Bu komut ile dosya taşıyabiliyoruz.

#$ grep
* Bu komut ile dosyalarda sözcük vs. arayabiliyoruz, çok kullanışlı bir komut.

#$ chmod
* Bu komut ile dosyaların yetkisini değiştirebiliyoruz, işte bu harika bir şey ama bir o kadarda korkunç bir komut tek bir komutla sisteminizi mahvedebilirsiniz.

#$ echo
* Bu komut çok güzel örneğin bir dosyadaki belli kelimeleri başka bir dosyaya yazdırabiliyorz. Diğer komutlarla iç içe kullanılabildiği için harika bir komut. Daha sonra çok detaylı anlatıcağım.

#$ cd
* Bu komut ile dizinler arası geçiş yapabilirsiniz.

#$ curl
* Bu komut ile HTTP GET/POST işlemleri yapabilirsiniz.
