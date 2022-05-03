# UiPath-ProductAndPrice

Input excel'i olarak sorgu atılacak siteleri ve CSS Selektörlerini yazıyoruz. (CSS Selektörlerin doğru çalışıp çalışmadığını Google Chrome F12 Incele ekranından kontrol edebilirsiniz. CSS Selektorler için kaynak: https://lnkd.in/d76NHhdS)

Süreci çalıştırdığımızda, herhangi bir UI işlemi olmadan arka planda sadece HTTP Request atarak ürün ismi ve fiyatını içeren bir excel dosyası hazırlanıyor. (HTTP Request'den dönen sayfayı AngleSharp kullanarak parse ettim.)
