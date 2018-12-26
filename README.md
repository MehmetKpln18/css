# Responsive CSS Türkçe
Responsive CSS Türkçe

HTML Mobil Responsive Oluşturmak için Türkçe Kaynak dosyası Oluşturmak İstedim.

1- Html sayfanıza head Kısmına Metayı ekleyin
<meta name="viewport" content="width=device-width, initial-scale=1.0">
  
2- responsive.css dosyası oluşturup aşağıdaki kodları yapıştırın.

/* Ekstra küçük cihazlar (telefonlar, 600px ve aşağı) */
@media only screen and (max-width: 600px) {
//CSS Kodları Buraya Gelecek.
}

/* Küçük cihazlar (dikey tabletler ve büyük telefonlar, 600px ve üstü) */
@media only screen and (min-width: 600px) {
//CSS Kodları Buraya Gelecek.
}

/* Orta boy aygıtlar (yatay tabletler, 768 piksel ve üstü) */
@media only screen and (min-width: 768px) {
//CSS Kodları Buraya Gelecek.
}

/* Büyük cihazlar (dizüstü bilgisayarlar / masaüstü bilgisayarlar, 992px ve üstü) */
@media only screen and (min-width: 992px) {
//CSS Kodları Buraya Gelecek.
}

/* Ekstra büyük cihazlar (büyük dizüstü bilgisayarlar ve masaüstü bilgisayarlar, 1200px ve üstü) */
@media only screen and (min-width: 1200px) {
//CSS Kodları Buraya Gelecek.
}

 3-Html sayfanıza head kısmına css dosyayı çağırın. <link rel="stylesheet" type="text/css" href="css/responsive.css">

