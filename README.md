# Insertion-Sort-Projesi 

patika.dev -> https://app.patika.dev/cataldirect

[22,27,16,2,18,6] -> Insertion Sort

1  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

    [22,27,16,2,18,6] -> [22| 27,16,2,18,6] 

    [22| 27,16,2,18,6] -> [22 27| 16,2,18,6]
    
    [22 27| 16,2,18,6] -> [22 27 16| 2,18,6]
                          [22 16 27| 2,18,6]
                          [16 22 27| 2,18,6]
                          
    [16 22 27| 2,18,6] -> [16 22 27 2| 18,6]
                          [16 22 2 27| 18,6]
                          [16 2 22 27| 18,6]
                          [2 16 22 27| 18,6]
                          
    [2 16 22 27| 18,6] -> [2 16 22 27 18| 6]
                          [2 16 22 18 27| 6]
                          [2 16 18 22 27| 6]
    [2 16 18 22 27| 6] -> [2 16 18 22 27 6]   
                          [2 16 18 22 6 27]
                          [2 16 18 6 22 27]
                          [2 16 6 18 22 27]
                          [2 6 16 18 22 27] <- SONUÇ
                      
2  Big-O gösterimini yazınız.
      
      Best case : O(n)
      Avg case ve Worst case : 0(n^2)
      
3  Time Complexity: 
    
    Average case: Aradığımız sayının ortada olması,
    Worst case: Aradığımız sayının sonda olması, 
    Best case: Aradığımız sayının dizinin en başında olması.
    
4  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

    Dizinin eleman sayısı çift sayılı olmasına rağmen 18 sayısı "average case" diyebiliriz. 
    
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

    [7,3,5,8,2,9,4,15,6] -> [7 | 3,5,8,2,9,4,15,6]
    
    [7 | 3,5,8,2,9,4,15,6] -> [7 3 | 5,8,2,9,4,15,6]
                              [3 7 | 5,8,2,9,4,15,6]
                              
    [3 7 | 5,8,2,9,4,15,6] -> [3 7 5 | 8,2,9,4,15,6]  
                              [3 5 7 | 8,2,9,4,15,6]
                              
    [3 7 5 | 8,2,9,4,15,6] -> [3 7 5 8 | 2,9,4,15,6]    <- SONUÇ                     
