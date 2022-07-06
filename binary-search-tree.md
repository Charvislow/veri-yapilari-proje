# Binary Search Tree

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary Search Tree

1. *Root, ilk eleman  7 oldugu icin 7 secilir.*

                        7
                        
2. 5, 7'den kucuk oldugu icin 7'nin soluna yazilir
                        
                        7
                       /
                      5
                      
3. 1, 7 ve 5'ten kucuk oldugu icin 5'in soluna yazilir
                         
                        7
                       /
                      5
                     /
                    1
                    
4. 8, 7'den buyuk oldugu icin 7'nin sagina yazilir
                          
                        7
                       / \
                      5    8
                     /
                    1
    
5. 3, 7 ve 5'ten kucuk oldugu icin 5'in soluna, 1'den buyuk oldugu icin 1'in sagina yazilir
 
                           
                        7
                       / \
                      5    8
                     / 
                    1    
                     \
                       3
                       
6. 6, 7'den kucuk oldugu icin 7'nin soluna, 5'ten buyuk oldugu icin 5'in sagina yazilir
                            
                        7
                       / \
                      5    8
                     / \
                    1    6
                     \
                       3
                       
7. 0, 7'den, 5'ten ve 1'den kucuk oldugu icin 1'in soluna yazilir
                             
                        7
                       / \
                      5    8
                     / \
                    1    6
                   / \
                  0    3
                  
8. 9, 7 ve 8'den buyuk oldugunda 8'in sagina yazilir
                             
                        7
                       / \
                      5    8
                     / \    \
                    1    6    9
                   / \
                  0    3
                  
9. 4, 7 ve 5'ten kucuk oldugu icin 5'in soluna, 1 ve 3'ten buyuk oldugu icin 3'un sagina yazilir
                             
                        7
                       / \
                      5    8
                     / \    \
                    1    6    9
                   / \
                  0    3
                        \
                          4
                          
10. 2, 7 ve 5'ten kucuk oldugu icin 5'in soluna, 1'den buyuk oldugu icin 1'in sagina ve 3'ten kucuk oldugu icin 3'un soluna yazilir
                             
                        7
                       / \
                      5    8
                     / \    \
                    1    6    9
                   / \
                  0    3
                      / \
                     2    4  
