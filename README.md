# Macera-Oyunu
Java Macera Oyunu

![image](https://github.com/aliylmztr/SQL-All_Projects/assets/123991935/cd85cd84-da7f-4768-a998-29e1530592ee)

<a href="https://www.patika.dev/tr">patika.dev </a>

----------------------------------------------

MACERA OYUNU

----------------------------------------------

Java ile metin tabanlı bir macera oyunu yapıyoruz.

----------------------------------------------

KARAKTERLER

----------------------------------------------

![image](https://github.com/aliylmztr/Macera-Oyunu/assets/123991935/8e8c9435-b502-4401-b88d-ff6f790f8bf8)

----------------------------------------------

CANAVARLAR

----------------------------------------------

![image](https://github.com/aliylmztr/Macera-Oyunu/assets/123991935/2675f6c9-9fe7-49da-bc49-1bfe2830b8a0)

----------------------------------------------

SİLAHLAR

----------------------------------------------

![image](https://github.com/aliylmztr/Macera-Oyunu/assets/123991935/cbfbbe0a-c657-4a2a-a0ca-985be2529569)

----------------------------------------------

ZIRHLAR

----------------------------------------------

![image](https://github.com/aliylmztr/Macera-Oyunu/assets/123991935/3560280a-861c-4b5f-b1ed-0eff5dede97c)


----------------------------------------------

MEKANLAR

----------------------------------------------

>> Güvenli Ev

Özellik : Can Yenileniyor

>> Mağara

Canavar : Zombi (1-3 Adet)

Özellik : Savaş + Ganimet

Eşya : Yemek (Food)

>> Orman

Canavar : Vampir (1-3 Adet)

Özellik : Savaş + Ganimet

Eşya : Odun (Firewood)

>> Nehir

Canavar : Ayı (1-3 Adet)

Özellik : Savaş + Ganimet

Eşya : Su (Water)

>> Mağaza
 
Özellik : Destekleyici Eşyalar Satın Almak

Silah : Tabanca,Kılıç,Tüfek

Zırh : Hafif,Orta,Ağır

----------------------------------------------

Sınıf Diyagramı

----------------------------------------------

![image](https://github.com/aliylmztr/Macera-Oyunu/assets/123991935/1a405ae7-1fbb-41fd-ac1d-233bdbe89a71)

----------------------------------------------

ÖDEVLER

----------------------------------------------

1- Oyunu bitirebilmek için savaş bölgelerindeki tüm düşmanlar temizlendikten sonra bölgeye özel ödülü oyunucun envanterine eklenmelidir. Eğer oyuncu tüm ödülleri toplayıp "Güvenli Eve" dönebilirse oyunu kazanır. Ayrıca ödül kazanılan bölgeye tekrar giriş yapılamaz.

>> Bölge Ödülleri

Mağara => Yemek (Food)

Orman => Odun (Firewood)

Nehir => Su (Water)

----------------------------------------------

2- Oyuncu bir canavarla karşılaştığında ilk hamleyi kimin yapacağını, %50 şans ile belirlenmesi. (Şuan ki durumda ilk vuran her zaman oyuncu)

----------------------------------------------

3- Yeni bir savaş bölgesi eklenmeli. Bu bölgenin amacı yenilen rakiplerden rastgele para, silah veya zırh kazanma ihtimali olması.

Bölge Adı : Maden

Canavar : Yılan (1-5 Adet)

Özellik : Savaş ve Ganimet

Eşya : Para, Silah veya Zırh

Yılan Özellikleri :

ID : 4

HASAR : Rastgele (3 ve 6 arası)

SAĞLIK :12

PARA : Yok (Onun yerine eşya kazanma ihtimali)

>> Yenilen bir rakiplerden düşen eşyalar :

> Silah Kazanma İhtimali : 15%

Tüfek Kazanma İhtimali : 20%

Kılıç Kazanma İhtimali : 30%

Tabanca Kazanma İhtimali : 50%

> Zırh Kazanma İhtimali : 15%

Ağır Zırh Kazanma İhtimali : 20%

Orta Zırh Kazanma İhtimali : 30%

Hafif Zırh Kazanma İhtimali : 50%

> Para Kazanma İhtimali : 25%

10 Para Kazanma İhtimali: 20%

5 Para Kazanma İhtimali: 30%

1 Para Kazanma İhtimali: 50%

> Hiç birşey kazanamama ihtimali : 45%
