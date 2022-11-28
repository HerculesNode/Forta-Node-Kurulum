# Forta Türkçe Kurulum Rehberi

<h1 align="center"> Forta </h1>
<h1 align="center"> <img src="https://raw.githubusercontent.com/herculessx/Forta-Node-Kurulum/main/indir.png" width="650"></h1>
<h1 align="center"> Selamlar,  Forta Her Hafta Ödüllü Kurulum rehberi by Hercules
</h1>


## 🟢 Bilgi

Şuanda Bir adet Forta Node Kurulum için 2500 Adet Fort Token gereklidir. Bu Tokenleri aşağıdaki Borsalardan yada Uniswap üzerinden temin edebilirsiniz. 
<br>Tüm işlemler Polygon ağında olacaktır. 
<br>

 * [Kucoin](https://www.kucoin.com/ucenter/signup?rcode=rPU3N98)
 * [Bybit](https://www.bybit.com/tr-TR/invite?ref=J89K9B)


### Linkler:

 * [Forta Takip Sistemi](https://scannerx.net)
 * [Forta Telegram Yardım Kanalımız](https://t.me/FortaDestek)
 * [Forta Discord Kanalı](https://discord.gg/H2gafvEbZN)
 * [Twitter](https://twitter.com/Hercules4413)
 * [Alchemy](https://www.alchemy.com/?r=badge:DM0NTMzMjcxNDkxM)



## 🟢 Kurulum
<br> 
Burada öncelikle Kurmak istediğimiz ağı seçiyoruz. Kurulum Otomatik olarak yapılacaktır. Toplamda 7 ağ üzerinden kurabiliriz. 
<br>Kurulum Aşamasında Bize lazım olacaklar listesi aşağıdaki gibidir.  

<br>1- Kurulum Esnasında 8 karakterli şifre özel karakter olmayacak Şifreyi not edin unutmayın. 
<br>2- Alchemy RPC adres
<br>2- Ödüllerin Geleceği Matemask cüzdanınız 
<br>2- Son olarak kurulum sonunda bize bir scanner adresi verecek buna verdiğimiz matemask üzerinden 0.1 matic yollayacağız




## 🟢 Kurulum Dosyaları <br>
1- Polygon <br>
```shell
wget -qO forta.sh https://scannerx.net/setup/forta.txt && chmod +x forta.sh && bash forta.sh
```
2- BSC <br>
```shell
wget -qO forta.sh https://scannerx.net/setup/fortabsc.txt && chmod +x forta.sh && bash forta.sh
```
3- Arbitrum <br>
```shell
wget -qO forta.sh https://scannerx.net/setup/fortaarbitrum.txt && chmod +x forta.sh && bash forta.sh
```
4- Avalanche <br>
```shell
wget -qO forta.sh https://scannerx.net/setup/fortaavalanche.txt && chmod +x forta.sh && bash forta.sh
```
5- Optimism <br>
```shell
wget -qO forta.sh https://scannerx.net/setup/fortaoptimism.txt && chmod +x forta.sh && bash forta.sh
```
6- Fantom <br>
```shell
wget -qO forta.sh https://scannerx.net/setup/fortafantom.txt && chmod +x forta.sh && bash forta.sh
```
7- ETH <br>
```shell
wget -qO forta.sh https://scannerx.net/setup/fortaethereum.txt && chmod +x forta.sh && bash forta.sh
```

<br><br>
Yukarıdaki ağlardan birini seçip Ubuntu konsolunuza girip Enter tuşuna basın daha sonra karşınıza aşağıdaki gibi bir ekran gelecek 1 seçip enter tuşuna basın ve kurulum başlayacaktır. 

<h1 align="center"> <img src="https://raw.githubusercontent.com/herculessx/Forta-Node-Kurulum/main/setup.png" width="650"></h1>


<br>
Kurulum esnasında setup sizden Şifre isteyecek 8 karakterli özel karakter olmasın "! gibi düz basit bir şifre girin 
<h1 align="center"> <img src="https://raw.githubusercontent.com/herculessx/Forta-Node-Kurulum/main/setup2.png" width="950"></h1>


<br>
Kurulum esnasında setup sizden hangi ağda kurulum yaptıysanız onunla ilgili RPC isteyecektir Alchemy üzerinden aldğımız RPC linkini giriyoruz. Hangi Ağda Kurulum yapıyor iseniz onun linkini girmek zorundasınız HTTPS ile başlayan link
<h1 align="center"> <img src="https://raw.githubusercontent.com/herculessx/Forta-Node-Kurulum/main/alchemyforta.png" width="950"></h1>

<br>
Kurulum esnasında setup sizden Matemask cüzdanınızı isteyecek ödüller bu cüzdana gelecek ve kurulum bitince bu cüzdandan fortanın size vermiş olduğu scanner adresine 0.1 matic yollayacağız.
<h1 align="center"> <img src="https://raw.githubusercontent.com/herculessx/Forta-Node-Kurulum/main/setupmate.png" width="950"></h1>

<br>
Ve kurulum bitti şimdi setup bize bir scanner adresi verdi. Aşağıdaki resimde görüldüğü gibi bu adrese biraz önce verdiğiniz Ana Matemask cüzdanımızdan 0.1 matic yollayacağız.
<h1 align="center"> <img src="https://raw.githubusercontent.com/herculessx/Forta-Node-Kurulum/main/fortaend.png" width="950"></h1>


<br>
Matemask adresimizden 0.1 matic yolladıktan sonra aşağıdaki Komutu girmemiz gerekiyor  girdikten sonra resimdeki gibi olmalıdır. 

```shell
forta register --owner-address MATEMASKADRESİNİZ --passphrase ŞİFRENİZ
```
<h1 align="center"> <img src="https://raw.githubusercontent.com/herculessx/Forta-Node-Kurulum/main/m1.png" width="950"></h1>

<br>
Ardından aşağıdaki komutları giriniz. Ve status bakınız

```shell
systemctl enable forta
systemctl start forta
systemctl status forta
```
<h1 align="center"> <img src="https://raw.githubusercontent.com/herculessx/Forta-Node-Kurulum/main/f1son.png" width="950"></h1>

<br><br>
Kurulum bitmiştir Scannerx.net üzerinden ücretsiz kayıt olup Nodenizi takip edebilir. Takıldığınız yerde Telegram destek kanalından soru sorabilir yada Forta Discord kanalından ulaşabilirsiniz. Bol Kazançlı günler dilerim.
