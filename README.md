# PowerBi-Kosullu Bicimlendirme-Calismasi

Ürün adı ve Toplam Satış 1 listelendi. 60k'dan büyük 150k'dan küçük satışlar maviye boyandı.
Toplam Satış 2 ve Toplam Miktar listelendi. Toplam Satış 2 üzerinden Temel aldığımız toplam miktarı 30 il 120 arasında olanlar sarı ile boyandı.

İşlem Sayısı = COUNTROWS( VALUES( Satis[SiparisKodu]))
Sıralama = RANKX(All(Urunler[UrunAdi]),[İşlem Sayısı],,DESC) ölçüleri oluşturuldu.

İşlem sayıs, Sıralama ve Toplam satış 3 listelendi. Toplam Satış üzerinden Sıralamayı temel alarak çeşitli renkler atandı.
