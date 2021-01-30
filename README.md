# wilkania<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset=utf-8>
        <link rel="stylesheet" href="stylesheet.css">
        <title>KREDIT RUMAH ANGIN RIBUT</title>
        
    </head>
    <body>
        <form action="itungan.php" method="POST">
            <b>Tipe Rumah :</b>
            <select nama="nama" id="" class="form-control" required>
                <option value="">-pilih-</option>
                <option value="Rose">Rose</option>
                <option value="Gold">Gold</option>
                <option value="Platinum">Platinum</option>
            </select><br>
            <b>Lama Angsuran:</b>
            <select value="jumlah" id="lama angsurannya" onchange="myFunction()" class="form-control"required>
                <option value="">-pilih-</option>
                <option value="12">12 Bulan</option>
                <option value="18">18 Bulan</option>
                <option value="24">24</option>
            
            </select><br>
            <input type="submit" name="kalkulasinya bossque" class="kalkulasinya" value="kalkulasi">
        </form>
        <hr>
        <?php
            if(isset($_POST["kalkulasinya"])){
                if($nama==Rose){$DP=24.000.000}
                elseif($nama==Gold){$DP=60.000.000}
                elseif($nama==Platinum){$DP=72.000.000}
            }
            
    </body>
</html>
