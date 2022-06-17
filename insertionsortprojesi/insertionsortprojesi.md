# Insertion Sort Projesi

 İlk olarak elimizdeki dizine bakalım

 [22,27,16,2,18,6]

 ---

 ## Insertion Sort aşamaları şu şekilde olmalıdır;

- İlk olarak en küçük olan değer belirlendikten sonra ilk baştaki ile yer değiştirir. ilk işlemden sonra elimizdeki rakamlar şu şekilde olmalıdır;

 [2,27,16,22,18,6]

 Gördüğünüz gibi '2' ve '22' değerleri yer değiştirdi. Çünkü '2' elimizdeki dizindeki en küçük sayı.

- Daha sonrasında yukarıdaki işlem aynı mantık ile devam eder ve elimizde aşağıdaki gibi bir dizin olur.

- [2,27,16,22,18,6]
- [2,6,16,22,18,27]
- [2,6,16,18,22,27]
- [2,6,16,18,22,27]

---

## Big-O gösterimi

- Big-O gösterimi Insertion Sort için O=n^2 şeklindedir. n değerimiz 6 olduğu için (çünkü dizin içerisinde 6 adet değerimiz var.) 6^2 den '36' sonucuna ulaşırız.

---

## Time Complexity

- Average case: Aradığımız sayının ortada olması

- Worst case: Aradığımız sayının sonda olması

- Best case: Aradığımız sayının dizinin en başında olması.

---

 ## Soru; Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

 - Dizi sıralandıktan sonra '18' sayısı Avarage case kapsamında girmektedir. Çünkü Best case durumumuz '2'. Worst case durumumuz ise '27' dir. Bu iki durum arasındaki bütün durumlar Avarage case kapsamına girmektedir.

---

 ## Soru; [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

 - [2,3,5,8,7,9,4,15,6]
 - [2,3,4,8,7,9,5,15,6]
 - [2,3,4,5,7,9,8,15,6]
 - [2,3,4,5,6,9,8,15,7]

 ---