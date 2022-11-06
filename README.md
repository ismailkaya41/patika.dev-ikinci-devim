# patika.dev-ikinci-devim
merge sort ödev
Proje 2 [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Merge Sort dizini 2 ye bölerek ilerler.
Bu yüzden diziyi ikiye bölüyoruz.
Tek eleman kalana kadar ayırmaya devam ediyoruz.
Sonra böldüklerimizi sırlayarak birleştiriyoruz. 
                      [16,21,11,8,12,22]

                   [16,21,11]   --  [8,12,22]
                 
                [16,21] - [11]  --  [8,12] - [22]
                
             [16] - [21] - [11] --  [8] - [12] - [22]
             
                [16,21] - [11]  --  [8,12] - [22]

                    [11,16,21]  --  [8,12,22]
                   
                        [8,11,12,16,21,22]  
Big-O gösterimini yazınız.
Merge sorting'de 2 ye bölerek işimizi kolaylaştırdığımız için big-o notation'ınımızı hesaplarken 2^x=n ---> x=logn kere bu işlemi yaptığımızı hesaplıyoruz önce.
Ve n tane satır için bu işlemi tekrarladğımız için big-o notation'ımız O(nlogn) oluyor.
