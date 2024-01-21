# VeriYapilariveAlgoritmalarProje 1

[22,27,16,2,18,6] -dizisinin sort türüne göre aşamaları

•	Başlangıç: [22,27,16,2,18,6]
1.	aşama: [22,27,16,2,18,6] (27, 22’den büyük olduğu için yer değiştirmeye gerek yok)
2.	aşama: [16,22,27,2,18,6] (16, 27’den küçük olduğu için 27’yi bir sonraki indekse kaydırıyoruz. 16, 22’den de küçük olduğu için 22’yi de bir sonraki indekse kaydırıyoruz. 16, dizinin başına geldiği için boş kalan yere yerleştiriyoruz.)
3.	aşama: [2,16,22,27,18,6] (2, 27’den küçük olduğu için 27’yi bir sonraki indekse kaydırıyoruz. 2, 22’den küçük olduğu için 22’yi bir sonraki indekse kaydırıyoruz. 2, 16’dan küçük olduğu için 16’yı bir sonraki indekse kaydırıyoruz. 2, dizinin başına geldiği için boş kalan yere yerleştiriyoruz.)
4.	aşama: [2,16,18,22,27,6] (18, 27’den küçük olduğu için 27’yi bir sonraki indekse kaydırıyoruz. 18, 22’den küçük olduğu için 22’yi bir sonraki indekse kaydırıyoruz. 18, 16’dan büyük olduğu için yer değiştirmeye gerek yok. 18’i boş kalan yere yerleştiriyoruz.)
5.	aşama: [2,6,16,18,22,27] (6, 27’den küçük olduğu için 27’yi bir sonraki indekse kaydırıyoruz. 6, 22’den küçük olduğu için 22’yi bir sonraki indekse kaydırıyoruz. 6, 18’den küçük olduğu için 18’i bir sonraki indekse kaydırıyoruz. 6, 16’dan küçük olduğu için 16’yı bir sonraki indekse kaydırıyoruz. 6, 2’den büyük olduğu için yer değiştirmeye gerek yok. 6’yı boş kalan yere yerleştiriyoruz.)
•	Sonuç: [2,6,16,18,22,27] 

Big-O (n²)

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı

Başlangıç: [7,3,5,8,2,9,4,15,6]

aşama: [2,3,5,8,7,9,4,15,6]

aşama: [2,3,4,8,7,9,5,15,6]

aşama: [2,3,4,5,7,9,8,15,6]

aşama: [2,3,4,5,6,9,8,15,7]
