<form method="post">
        1.sayi:<input type="number" name ="sayi1"><br>
        1.sayi:<input type="number" name ="sayi2"><br>
        <select name="islem">
            <option value="">secınız</option>
            <option value="1">topla</option>
            <option value="2">cikart</option>
            <option value="3">carp</option>
            <option value="4">bol</option>
            <option value="5">kalan</option>
</select><br>
<button type="submit">hesapla</button>
</form>
<div>
    <h3>islem sonucu</h3>
    <?php
    if($_SERVER['REQUEST_METHOD']=="POST"){
        $sayi1=$_POST['sayi1'];
        $sayi2=$_POST['sayi2'];
        $islem=$_POST['islem'];
        if($islem ==1){
            echo $sayi1+$sayi2;
        }elseif($islem==2){
            echo $sayi1-$sayi2;
        }elseif($islem==3){
            echo $sayi1*$sayi2;
        }
    elseif($islem==4){
        echo $sayi1/$sayi2;
    }elseif($islem==5){
        echo $sayi1%$sayi2;
        }
    }
    ?>
