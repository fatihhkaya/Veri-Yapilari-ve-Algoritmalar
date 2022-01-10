[22,27,16,2,18,6]---> Insertion Sort 

 1.Yukarıdaki verilen dizinin sort türüne göre aşamalarını yazınız.

 Cevap: 
   |
   |---> 1.durum [22,27,16,2,18,6]  n

         2.durum [|2|,27,16,22,18,6]  n-1

         3.durum [|2|,|6|,|16|,22,18,27]  n-2

         4.durum [|2|,|6|,|16|,|18|,22,27]  1

       

2. Big-O gösterimini yazınız.

Cevap: 
  |
  |----> O(n²)


3. Time Complexity: Average case: Aradığımız sayının ortada olması,
                        |
                      Cevap:   |--> O(n²) --> O(6²) --> O(36)

                    Worst case: Aradığımız sayının sonda olması,    
                        |
                      Cevap:   |--> O(n²) --> O(6²) --> O(36)

                    Best case: Aradığımız sayının dizinin en başında olması.    
                        |
                      Cevap:   |--> O(n) --> O(6)


4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
      |
      |---> Average Case





[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

       1.durum [7,3,5,8,2,9,4,15,6] 

       2.durum [|2|,|3|,5,8,7,9,4,15,6] 

       3.durum [|2|,|3|,|4|,8,7,9,5,15,6] 

       3.durum [|2|,|3|,|4|,|5|,7,9,8,15,6] 

       4.durum [|2|,|3|,|4|,|5|,|6|,9,8,15,7] 

       5.durum [|2|,|3|,|4|,|5|,|6|,|7|,|8|,15,9] 

       6.durum [|2|,|3|,|4|,|5|,|6|,|7|,|8|,|9|,15] 