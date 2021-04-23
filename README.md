# Praktikum 4
# Pemrograman Web
```
Mardiansyah
311910263
TI.19.C.1
Universitas Pelita Bangsa
```
## Langkah-langkah Praktikum
Persiapan membuat dokumen HTML dengan nama file lab4_box.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Box Element</title>
</head>
<body>
<header>
<h1>Box Element</h1>
</header>
</body>
</html>
```

## Membuat Box Element
Kemudian tambahkan kode untuk membuat box element dengan tag div seperti berikut.
```
<section>
<div class="div1">Div 1</div>
<div class="div2">Div 2</div>
<div class="div3">Div 3</div>
</section>
```

## CSS Float Property
Selanjutnya tambahkan deklarasi CSS pada head untuk membuat float element, seperti berikut.
```
<style>
div {
float:left;
padding: 10px;
}
.div1 {
background: red;
}
.div2 {
background: yellow;
}
.div3 {
background: green;
}
</style>
```

Kemudian buka browser untuk melihat hasilnya.

## Mengatur Clearfix Element
Clearfix digunakan untuk mengatur element setelah float element. Property clear digunakan untuk
mengaturnya.
Tambahkan element div lainnya seteleah div3 seperti berikut.
```
<section>
<div class="div1">Div 1</div>
<div class="div2">Div 2</div>
<div class="div3">Div 3</div>
<div class="div4">Div 4</div>
</section>
```

Kemudian atur property clear pada CSS, seperti berikut.

```
.div4 {
background-color: blue;
clear: left;
float: none;
```

Selanjutnya buka browser dan refresh kembali.
