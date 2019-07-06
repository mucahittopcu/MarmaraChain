**Oracle VirtualBox ile Ubuntu Kurulumu**

VirtualBox sayesinde bilgisayarımıza sanal makine kurabiliriz. Sanal Makine=?? diye sorarsanız… Arakdaşlar sanal makine , bilgisayarınız sanki iki makine(kasa/anakart) birden varmış gibi davranır.Yani siz hayali olarak bir bilgisayar daha kullanmaya başlarsınız.Bu kavramı zamanla daha iyi anlarsınız..

**Öncelikle bilgisayarımıza kurmamız gereken programlar;**

**[Oracle VirtualBox 4.1.8 Final Türkçe ](https://download.virtualbox.org/virtualbox/6.0.4/VirtualBox-6.0.4-128413-Win.exe)  (32-64bit Buradan indirebilirsiniz)

**[Ubuntu 18.04 Masaüstü Sürümü ](http://releases.ubuntu.com/18.04/ubuntu-18.04.2-desktop-amd64.iso)              (32/64bit  Buradan indirebilirsiniz)

**1-Öncelikle VirtualBox da Sanal Makine Oluşturmak**

Programımızı basit bir şekilde kurduktan sonra, sıradaki işlemler
     ** Öncelikle ‘Yeni’ ye basarak yeni bir tane daha oluşturuyoruz.Yanda ki fotoğrafta gördüğünüz ”MyUbuntu” benim kurulu sanal makinem. Şimdi sizler için bir tane  daha kuracağım.
     
![JZGZkQ](https://user-images.githubusercontent.com/3285283/54093218-65057780-43a6-11e9-8756-6a0717427ded.jpg)

 İşte sanal makine sihirbazımız çalışmaya başladı. Buradan Next(ileri) diyerek devam ediyoruz.
![21](https://user-images.githubusercontent.com/3285283/54093253-faa10700-43a6-11e9-80c5-bd4a77c11210.jpg)

Bu kısımda resimlere de not ettiğim gibi ‘İsim’ kısmına,
Sanal Makinenize vermek istediğiniz ismi yazmalısınız.
Ben örnek olarak ‘Sanalmakinem’ diyeceğim.

![31](https://user-images.githubusercontent.com/3285283/54093304-756a2200-43a7-11e9-9653-95cf12f13566.jpg)

Bu kısımda, kırmızı çerçeveye aldığım kısım gibi, bizden  ‘sanalmakinem’ için ayırmak istediğiniz bellek boyutunu soruyor.
Resimlerin üstüne not ettiğim gibi bilgisayardan bilgisayara değişen bir değerdir.
**Not: 2048 yani 2 gb ram yapıyoruz ileri diyoruz ( isteğe göre daha yüksek yapabilirsiniz fakat EN DÜŞÜK 2048 MB OLMASI GEREKİYOR.**
![4](https://user-images.githubusercontent.com/3285283/54093318-a2b6d000-43a7-11e9-8f1b-bd8f20e15417.jpg)

Sabit Disk oluşturmamız gerekiyor. "Şİmdi sanal disk oluştur" seçeneğini seçip Oluştur butonuna basıp ilerliyoruz.
DİKKAT UYARI! HDD ALANINI 10GB YERİNE 30 GB SEÇMELİSİNİZ. AKSİ HALDE SORUN YAŞARSINIZ.
![5](https://user-images.githubusercontent.com/3285283/54093357-3092bb00-43a8-11e9-83b1-22de62525797.png)

Resimde ki gibi devam.

![61](https://user-images.githubusercontent.com/3285283/54093370-5d46d280-43a8-11e9-8c1e-63f939ad2c39.jpg)

Resimde ki gibi devam 2.

![7](https://user-images.githubusercontent.com/3285283/54093384-90896180-43a8-11e9-87de-b8835992176c.jpg)

Create butonuna basıyoruz.

![9](https://user-images.githubusercontent.com/3285283/54093405-a72fb880-43a8-11e9-8c12-fa9334ef2082.jpg)

Sanal Makinemiz oluşturuldu.

![10](https://user-images.githubusercontent.com/3285283/54093420-c595b400-43a8-11e9-9e1e-6c5a4d0547d3.jpg)




**2-Sanal Makine’ye Ubuntu Kurulumu**
Şu anda sanal makinemizin özelliklerini belirledik.Onun için bölüm ayırdık Ubuntu kurulumuna geçiyoruz.  Ondan sonra sanal makinemizi kullanabiliriz.

Resimde ki gibi başlat butonuna basıyoruz.
![11](https://user-images.githubusercontent.com/3285283/54093454-173e3e80-43a9-11e9-8e4a-8ffbb89798df.jpg)

Sanal makinemizi açılmaya başladığında işletim sistemini CD/DVD ROM dan mı yoksa bilgisayarınızda kayıtlı olan .iso dosyasından mı kuracağız onu seçiyoruz.  İndirdiğimiz Ubuntu 18.04 iso dosyasını bulup seçiyoruz.
![121](https://user-images.githubusercontent.com/3285283/54093474-481e7380-43a9-11e9-9d3a-1201de555210.jpg)

Karşınıza ilk kurulum çıkacaktır. Oradan devam ederek de Ubuntu'yu kurabilirsiniz.Eğer ki ben ilk kurulumu kaçırdım yapamadım derseniz  bi başka yolda,

sanal makinemizi çalıştırdığında en üstteki aygıtlar sekmesinden yapabiliyoruz. Üsteki resmi inceleyebilirsiniz.

Orada Choose a virtual CD DVD disk file ‘ı seçerseniz .iso dosyanızla kurabilirsiniz
ya da Host Drive E:/ seçerek de CD/DVD  kullanarak yapabilirsiniz.

**Sırada ki işlem Ubuntu ‘ yu kurmak..**

Ubuntu Kur’a tıklıyoruz. ve resimlerdeki gibi basit ayarlamalarınızı yapıp yönergeleri takip ediyoruz.
![121](https://user-images.githubusercontent.com/3285283/54093539-e14d8a00-43a9-11e9-9b72-e20c70a4b453.jpg)
![13](https://user-images.githubusercontent.com/3285283/54093542-ea3e5b80-43a9-11e9-9f10-8eb9bd15a4ee.jpg)

Arkadaşlar bundan sonrası kolay

Klavye seçimi yapıyorsunuz,

Yerinizi(Sinop/İstanbul vb. ) giriyorsunuz.

Kurulum tamamen temiz bittikten sonra bu konudan devam edebilirsiniz. 
[Marmara Kredi döngüsü - vadeli çek açıklamalı anlatım.(Türkçe)](https://github.com/marmarachain/MarmaraChain/issues/4)
