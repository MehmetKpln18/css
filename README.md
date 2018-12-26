# Responsive CSS Türkçe
Responsive CSS Türkçe

HTML Mobil Responsive Oluşturmak için Türkçe Kaynak dosyası Oluşturmak İstedim.

1- Html sayfanıza head Kısmına Metayı ekleyin
<meta name="viewport" content="width=device-width, initial-scale=1.0">
  
2- responsive.css dosyası oluşturup aşağıdaki @media only screen kodları yapıştırın

@media only screen and (max-width: 600px) {
/* Ekstra küçük cihazlar (telefonlar, 600px ve aşağı) */
}


@media only screen and (min-width: 600px) {
/* Küçük cihazlar (dikey tabletler ve büyük telefonlar, 600px ve üstü) */
}


@media only screen and (min-width: 768px) {
/* Orta boy aygıtlar (yatay tabletler, 768 piksel ve üstü) */
}


@media only screen and (min-width: 992px) {
/* Büyük cihazlar (dizüstü bilgisayarlar / masaüstü bilgisayarlar, 992px ve üstü) */
}


@media only screen and (min-width: 1200px) {
/* Ekstra büyük cihazlar (büyük dizüstü bilgisayarlar ve masaüstü bilgisayarlar, 1200px ve üstü) */
}

3-Html sayfanıza head kısmına css dosyayı çağırın. 
<link rel="stylesheet" type="text/css" href="css/responsive.css">

İsterseniz Dosyayı direk indirip sitenizi hazırlamaya başlayabilirsiniz.
