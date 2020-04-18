# Windows ile MCL (Marmara Credit Loops) zincire bağlanıp yeni cüzdan, staking ve mining oluşturma.

ilk olarak linkteki **Win-MCL.zip** dosyasını indiriyoruz. http://www.marmara.io/guifiles/Win-MCL.zip

## Adımları uyguluyoruz.

## 1. adım
- **Win-MCL.zip** dosyasını `"C:\"` ana dizine atın.
- **Win-MCL.zip** dosyasını sağ tıklayıp klasöre çıkart diyoruz.
- `"C:\Win-MCl"` klasörüne girin.
-  Klasördeki **fetch-params.bat** çift tıklayarak çalıştırıp **ZcashParams** dosyalarını çekiyoruz. (1.5 gb civarıdır. internet hızınıza göre zaman alabilir beklemesiniz.!!!)

![Komodo Logo](img/Screenshot_107.png "Marmara Credit")



## 2. adım (Path yolu için aşağıdaki resimlerde anlattıldığı gibi sırayla yapınız.)

- Girilecek path yolu : `"C:\Win-MCL"`
- adım 1
![Komodo Logo](img/path-1.jpg "Marmara Credit")
- adım 2 
![Komodo Logo](img/path-2.jpg "Marmara Credit")
- adım 3
![Komodo Logo](img/path-3.png "Marmara Credit")


## 3. adım zinciri başlatma.

- 2 adet MSDOS konsolu Açıyoruz (Win+R veya > başlat cmd yazarak "Command Prompt" açabilirsiniz.)
- ilk ekrana MCl zinciri başlatma komutunu giriyoruz. (blokları çekmesini bekliyoruz.)

```komodod -ac_name=MCL -ac_supply=2000000 -ac_cc=2 -addnode=37.148.210.158 -addnode=37.148.212.36 -addressindex=1 -spentindex=1 -ac_marmara=1 -ac_staked=75 -ac_reward=3000000000```
- resim
![Komodo Logo](img/resim1.png "Marmara Credit")

## Zincire bağlandık!
Not : - blokları çekerken 2. ekranda blokzincirini kontrol edebilir, yeni cüzdan adresi oluşturarak "pubkey" alıp zinciri durdurup pubkey ile yeniden başlatabiliriz. ( zincire bağlandık artık. istediğimiz gibi hesabımızı kontrol edebiliriz.)

# Zincirde yeni  cüzdan adresi oluşturup pubkey ile başlatma.

- yeni cüzdan adresi oluşturuyoruz. ve pubkey alıyoruz.

- cüzdan oluşturma komutu :
```komodo-cli -ac_name=MCL getnewaddress```
- pubkey alma komutu : 
```komodo-cli -ac_name=MCL validateaddress "walletadresi"```
![Komodo Logo](img/resim2.png "Marmara Credit")
- bilgileri kaydediyoruz.
![Komodo Logo](img/resim3.png "Marmara Credit")
- zinciri durdurup pubkey ile başlatıyoruz.
 - - zinciri durdurma 
 - - ```komodo-cli -ac_name=MCL stop```
 - - zinciri durdurma pubkey ile başlatma

 - - ```komodod -ac_name=MCL -ac_supply=2000000 -ac_cc=2 -addnode=37.148.210.158 -addnode=37.148.212.36 -addressindex=1 -spentindex=1 -ac_marmara=1 -ac_staked=75 -ac_reward=3000000000 -pubkey=03bb140553b21bbd10964013eba8c2bbb54c750247fcd3117f604a9c01c79f5da0```
 ![Komodo Logo](img/resim4.png "Marmara Credit")

 ## Zincire pubkeyimiz ile başlattık!

 ### şimdi mining ve staking yapma komutları (2. ekranda yapılacaktır.)
 
 - mining ve staking kontrol etme.
 - - ```komodo-cli -ac_name=MCL getgenerate```
  ![Komodo Logo](img/resim5.png "Marmara Credit")

- Staking açma
- - ```komodo-cli -ac_name=MCL setgenerate true 0```
![Komodo Logo](img/resim6.png "Marmara Credit")

- Mining açma
- - ```komodo-cli -ac_name=MCL setgenerate true 1```
![Komodo Logo](img/resim7.png "Marmara Credit")

- Mining ve Staking kapatma.
- - ```komodo-cli -ac_name=MCL setgenerate false```
![Komodo Logo](img/resim8.png "Marmara Credit")



## genel kontrol komutları.

- wallet info kontrol.
- - ```komodo-cli -ac_name=MCL marmarainfo 0 0 0 0 "pubkey"```
![Komodo Logo](img/resim9.png "Marmara Credit")