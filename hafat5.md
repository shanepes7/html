$y=123; $x=12; Echo $x

$x=89; function deneme(){ küresel $x; Echo $x; } deneme();

$x=89; function deneme(){ Echo $GLOBALS['x'];

} deneme();

$metin ='merhaba'; baskı($metin);

$x=3.14; var_dump($x);

$x=doğru; $y=yanlış; var_dump($x)

$araba =array ("Mercedes", "BMW", "Volvo"); var_dump($araba)

$a=null; var_dump($a);

dedefine ("MERHABA", "DUNYA"); yankı MERHABA;

Echo strlen ("Merhaba Dunya");

Echo str_word_count("Merhaba Dunya");

echo strrev ("selam");

Echo strpos ("Merhaba Dunya", "Dunya");

Echo strrpos ("Merhaba Dunya","A");

Echo Strtoupper ("Merhaba Dunya");

echo strtolower ("MERHABA DUNYA");

Echo str_replace("a","e","merhaba dunya");

echo $x=" rizgar "; echo '
'; yankı trim($x);

$x="merhaba dunya"; $dizi=patlama(" ",$x); var_dump($dizi)

$x="merhaba dunya"; $dizi=patlama(" ",$x); echo $dizi[0];

$x="merhaba dunya"; echo substr($x,8,5);

Echo str_repeat("Selam ",10);

Echo "Merhaba "Ruzgar"";

function aciklamakisalt($aciklama,$karaktersayisi=50){ if(strlen($aciklama) <50){ $aciklama dön; } $kisalt= substr($aciklama,0,50); $sonbosluk=strrpos($kisalt, " "); return substr($kisalt,0,$sonbosluk). "..."; } $metin="UBIS sisteminde kişisel işlemlerinizi yapabilmeniz için size özel tanımlanmış kullanıcı adı ve şifreniz ile yukarıdaki Kullan formundan giriş"; echo '
'; echo aciklamakisalt($metin,50);

function epostagizle($eposta){ $sonuc=patlama("@", $eposta); $ilkkisim=substr($sonuc[0],0,3); $yildizli=str_repeat("*", strlen ($sonuc[0])-3); geri $ilkkisim. $yildizli . "@". $sonuc[1]; } echo epostagizle("babayewsanepes@gmail.com")
