
# �li�ki

-  Nesne Y�nelimli Programlama (Object Orientited Programming - OOP ) dillerinin en b�y�k avantajlar�ndan birisi de yazd���m�z kodu tekrar kullanabilme �zelli�idir. Bu yeniden kullan�labilirlik, s�n�flar aras�ndaki ili�kiden dolay� m�mk�nd�r.
-   Nesneye y�nelik programlama genellikle 4 t�r ili�kiyi destekler: kal�t�m, ili�kilendirme, kompozisyon ve toplama. B�t�n bu ili�kiler "Is-A" , "Has-A" ve "Part of " ili�kisine dayanmaktad�r.

## Kal�t�m :


- Kal�t�m �IS-A� ili�ki t�r�d�r. �IS-A� ili�kisi tamamen S�n�f Kal�t�m� veya Aray�z Kal�t�m� �eklinde olabilen  iki t�r mirasa dayanmaktad�r. Kal�t�m, var olan s�n�f kodunu kullanarak yeni bir s�n�f yaratt���m�z bir ebeveyn-�ocuk ili�kisidir. Bu sadece �A�n�n t�r� B� demek gibi bir �ey. 
 �rne�in �Elma bir meyvedir�, �Ferrari bir arabad�r�.

 

 - Daha iyi anla��lmas� i�in ger�ek bir d�nya senaryosu ele alal�m.

 - HOD bir kolej personelidir.

 - T�m ��retmenler kolej personelidir.

 - HOD ve ��retmenler koleje girmek i�in kimlik kart�na sahiptir.

- HOD'un talimat�na g�re �al��an bir personeli var.

- HOD, dersi belirli bir zaman diliminde kapsayacak �ekilde ��retmenin �al��malar�n� �stlenme sorumlulu�una sahiptir.

�lk iki varsay�m� ele alal�m: �HOD kolej personelidir� ve �T�m ��retmenler kolej personelidir�. Bu varsay�m i�in bir �Personel� �st s�n�f� olu�turabilir ve bu �st s�n�f�n� �HOD� ve ���retmen� s�n�flar�nda miras alabiliriz.




## Kompozisyon :


- Basit�e kompozisyon, di�er nesnelere referans olan �rnek de�i�kenlerinin kullan�lmas� anlam�na gelir. Kompozisyon ili�kisinde her iki varl�k da birbirine ba�l�d�r; �rne�in �motor araban�n bir par�as�d�r�, �kalp v�cudun bir par�as�d�r�.

-  Araba ve motor �rne�ini ele alal�m. Motor araban�n bir par�as�d�r ve her ikisi de birbirine ba�l�d�r.


## �li�kilendirme :


- �li�kilendirme �Has-A� tipi bir ili�kidir. �li�kilendirme b/w adl� iki s�n�f� kullanarak ili�kilerini kurar. �li�kilendirme ili�kileri birebir, bire �ok, �oka bir ve �oka �ok olabilir. �rne�in, iki s�n�f�m�z oldu�unu varsayal�m, o zaman bu iki s�n�f�n her ikisi de birbirlerinin nesnesini baz� i�ler i�in payla��rlarsa ve ayn� zamanda birbirlerinin ba��ml�l��� olmadan var olabilirlerse veya her ikisinin de kendi �m�rleri varsa, "Has-A" ili�kisi oldu�u s�ylenir.


## Toplama :


- Toplama, "has-a" ili�kisine dayan�r. Toplama �zel bir ili�kilendirme �eklidir. �li�kilendirilmi� olarak, herhangi bir s�n�f (varl�k) sahibi olarak �al��mamakta, toplamda bir varl�k sahibi olarak �al��maktad�r. Birle�mede, her iki varl�k da baz� i�ler i�in bulu�uyor ve sonra ayr�l�yorlar. Toplama tek y�nl� bir ili�kilendirmedir.

 
 ���renci� ve �adres� �rneklerini ele alal�m. Her ��rencinin bir adresinin olmas� gerekir, b�ylece ��renci s�n�f� ve Adres s�n�f� �Has-A� t�r� bir ili�ki olacakt�r, ancak bunun tersi do�ru de�ildir (her adresin bir ��rencinin i�ermesi gerekmez). �yleyse ��renci, i�letme sahibi olarak �al���r. Bu bir toplama ili�kisi olacakt�r.