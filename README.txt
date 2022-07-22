Projede ilk olarak dosya yolu doğru verilip verilmediği kontorl edilmelidir.
Listboxta görülen linelara göre çizim yapılmaktadır.
Listboxtan item seçilmeli eğer tanımladığınız dizide color veya pen değerleri belirlenmemişse panelde bulunan comboxtan size'ı buttondan da 
colordialog yardımıyla yeni renginizi belirleyebilirsiniz.
Listboxtan seçim yapıldıktan sonra Draw buttonu ile formun ortasına istenen çizim yapılmaktadır.
Eğer büyük boyutlu sayılar girerseniz ekrandan taşma olasılığı bulunmaktadır.
L F R COLOR PEN gibi token anahtar kelimleri yan yana kullanmayınız kullandıktan sonra değerini yazmayı unutmayınız.
Metinse olarak RED anahtar kelimesi R ile karıştığı için çıkarılmıştır. RED için paneli tercih ediniz.
Draw buttonunu kullandıktan sonra çizim yapılır ve button görümez hale gelir Reset Buttonu aktifleşir.
Reset butonu sayesinde program ilk haline geri getirilir.
En alt kısımda hata oluştuğu zaman uyarı vermektedir.
Çizim bitene kadar beklemeniz istenmektedir.
Üst üste tokenları kullanmayınız her blokta yalnızca her token bir kere kullanmayı tercih ediniz. Örnek olarak 
[PEN 10 PEN 5] kullandığınız zaman en sonda bulunan PEN 5 tanımlanacaktır.