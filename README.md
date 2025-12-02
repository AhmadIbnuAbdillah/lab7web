# lab7web
Nama:  Ahmad Ibnu Abdillah <br>
Kelas: TI.24.A.5 <br>
NIM:   312410489 <br>

# Kode dan Dokumentasi
```
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <title>PHP Dasar</title>
</head>
<body>
 <h1>Belajar PHP Dasar</h1>
 <?php
 echo "Hello World";
 ?>
</body>
</html>
```
![img](https://github.com/AhmadIbnuAbdillah/img7/blob/a3ebecdedd631eb920a849e55e63e2ae7ef4ab03/Screenshot%202025-12-02%20204919.png)
```
<?php
$nim = "0411500400";
$nama = 'Abdullah';
echo "NIM : " . $nim . "<br>";
echo "Nama : $nama";
?>
```
![img](https://github.com/AhmadIbnuAbdillah/img7/blob/a3ebecdedd631eb920a849e55e63e2ae7ef4ab03/Screenshot%202025-12-02%20204957.png)
```
<?php
echo 'Selamat Datang ' . $_GET['nama'];
?>
```
![img](https://github.com/AhmadIbnuAbdillah/img7/blob/a3ebecdedd631eb920a849e55e63e2ae7ef4ab03/Screenshot%202025-12-02%20211903.png)
```
<?php
$gaji = 1000000;
$pajak = 0.1;
$thp = $gaji - ($gaji*$pajak);
echo "Gaji sebelum pajak = Rp. $gaji <br>";
echo "Gaji yang dibawa pulang = Rp. $thp";
?>
```
![img](https://github.com/AhmadIbnuAbdillah/img7/blob/a3ebecdedd631eb920a849e55e63e2ae7ef4ab03/Screenshot%202025-12-02%20212225.png)
```
<?php
$nama_hari = date("l");
if ($nama_hari == "Sunday") {
 echo "Minggu";
} elseif ($nama_hari == "Monday") {
 echo "Senin";
} else {
 echo "Selasa";
}
?>
```
![img]()
```
<?php
echo "Perulangan 1 sampai 10 <br />";
for ($i=1; $i<=10; $i++) {
 echo "Perulangan ke: " . $i . '<br />';
}
echo "Perulangan Menurun dari 10 ke 1 <br />";
for ($i=10; $i>=1; $i--) {
 echo "Perulangan ke: " . $i . '<br />';
}
?>

```
![img](https://github.com/AhmadIbnuAbdillah/img7/blob/a3ebecdedd631eb920a849e55e63e2ae7ef4ab03/Screenshot%202025-12-02%20212507.png)
```
<?php
echo "Perulangan 1 sampai 10 <br />";
$i=1;
while ($i<=10) {
 echo "Perulangan ke: " . $i . '<br />';
 $i++;
}
?>
```
![img](https://github.com/AhmadIbnuAbdillah/img7/blob/a3ebecdedd631eb920a849e55e63e2ae7ef4ab03/Screenshot%202025-12-02%20212557.png)
