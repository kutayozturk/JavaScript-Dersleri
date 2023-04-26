# JavaScript - ilk Örnek

JavaScript: Geliştiricilerin etkileşimli web sayfaları oluşturmak için kullandığı bir programlama dilidir.

javascript, doğrudan **html** uzantılı bir dosyanın içerisine yazılabildiği gibi, dışarıda ayrıca hazırlanıp, **html** içerisinde çağrılabilir.
javascript dosyasının uzantısı **.js**'dir.


Bir HTML kodları içerisinde herhangi bir yerde 
```
<script type="text/javascript"> 

ETİKETLERİ ARASINA 

</script> 
```
komutları yer almalıdır. Bu komtuların
```
<body>

</body>
```
etiketleri arasında yer alması doğru bir kullanım şeklidir.


Açağıdaki kod bütünü incelendiğinde, **html** içerisinde **javascript** kullanıldığı görülmektedir.

```

<html>
    <head>

    </head>
        <body>
            <script type="text/javascript">
                document.write("Merhabalar"); 
            </script>
        </body>
</html>

```

Yukarıdaki örnekten de anlaşılacağı üzere,
```
document.write("Ekrana Yazdır"); 
```
komutu ile ekrana yazı yazdırdık.