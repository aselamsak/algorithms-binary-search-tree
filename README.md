# Patika.dev Binary Search Tree

* Patika Profil Linki:  https://app.patika.dev/sakas

## Ödev 


* [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary Search Tree aşamalarını yazınız.
  
  * Binary search tree, her düğümün solundaki koldan ulaşılabilecek bütün verilerin düğümün değerinden küçük, sağ kolundan ulaşılabilecek verilerin değerinin o düğümün değerinden büyük olmasını şart koşar. Bunu göz önüne alarak dizi elemanlarını sırayla ekleyelim;
    
    * Root elemanı 7 olarak başlanır.
    
                              7
                              
    * 5 sayısı 7 den küçük olduğundan 7 nin soluna eklenir.
      
                              7
                             /
                            5
       
    * 1 sayısı 7 den küçük olduğu için 7 nin soluna bakılır, 5 ten de küçük olduğu için 5 in soluna eklenir.
     
                               7
                              / 
                             5   
                            /
                           1
                           
    * 8 sayısı 7 den büyük olduğu için 7 nin sağına eklenir.
     
                                   7
                                  / \
                                 5   8
                                /
                               1
                               
    * 3 sayısı 7 den küçük olduğu için 7 nin soluna bakılır, 5 ten küçük olduğu için 5 in soluna bakılır, 1 den büyük olduğu için 1 in sağına eklenir.
     
                                   7
                                  / \
                                 5   8
                                /
                               1
                                \
                                 3
    
    * 6 sayısı 7 den küçük olduğu için 7 nin soluna bakılır, 5 ten büyük olduğu için 5 in sağına eklenir.
     
                                   7
                                  / \
                                 5   8
                                / \ 
                               1   6
                                \
                                 3
                                 
    * 0 sayısı 7 den küçük olduğu için 7 nin soluna bakılır, 5 ten küçük olduğu için 5 in soluna bakılır, 1 den küçük olduğu için 1 in sağına eklenir
     
                                   7
                                  / \
                                 5   8
                                / \ 
                               1   6
                              / \
                             0   3
                             
    * 9 sayısı 7 den büyük olduğu için 7 nin sağına bakılır, 8 den büyük olduğu için 8 in sağına eklenir.
     
                                   7
                                  / \
                                 5   8
                                / \   \
                               1   6   9
                              / \
                             0   3
                             
    * 4 sayısı 7 den küçük olduğu için 7 nin soluna bakılır, 5 ten küçük olduğu için 5 in soluna bakılır, 1 den büyük olduğu için 1 in sağına bakılır, 3 ten büyük olduğu için 3 ün sağına eklenir.
     
                                   7
                                  / \
                                 5   8
                                / \   \
                               1   6   9
                              / \
                             0   3
                                  \
                                   4
                                   
    * 2 sayısı 7 den küçük olduğu için 7 nin soluna bakılır, 5 ten küçük olduğu için 5 in soluna bakılır, 1 den büyük olduğu için 1 in sağına bakılır, 3 ten küçük olduğu için 3 ün soluna eklenir.
     
                                   7
                                  / \
                                 5   8
                                / \   \
                               1   6   9
                              / \
                             0   3
                                / \
                               2   4
                                 
