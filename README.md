Merge Sort, birleştirme (merge) ve bölme (divide) işlemleriyle çalışan bir sıralama algoritmasıdır. Verilen diziyi sürekli olarak ikiye bölerek her bir alt dizi için sıralama yapar, ardından bu alt dizileri birleştirerek sonuçta sıralı bir dizi elde eder.

Verilen dizi: [16, 21, 11, 8, 12, 22]

Aşamaları:

[16, 21, 11] [8, 12, 22] (Diziyi ikiye böldük)

[16, 21] [11] [8, 12] [22] (Her bir alt diziyi ikiye böldük)

[16] [21] [11] [8] [12] [22] (Her bir alt diziyi ikiye böldük)

[16, 21] [8, 11] [12, 22] (Tek elemanlı dizileri birleştirdik)

[8, 11, 16, 21] [12, 22] (Her bir çifti birleştirdik)

[8, 11, 12, 16, 21, 22] (Son olarak iki büyük alt diziyi birleştirdik)

Sıralanmış dizi: [8, 11, 12, 16, 21, 22]

Big-O Gösterimi:
Merge Sort'un zaman karmaşıklığı O(n log n) olarak ifade edilir. Burada 'n', dizi elemanlarının sayısıdır. Merge Sort, büyük ve sıralı olmayan dizilerde de etkin çalışabilen bir sıralama algoritmasıdır. Ancak n log n büyüklüğündeki zaman karmaşıklığı nedeniyle büyük veri kümesi için daha tercih edilebilir olabilmektedir.
