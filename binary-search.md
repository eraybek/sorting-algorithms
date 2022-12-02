#binary-search

<h3>Soru</h3>
<h5>1- [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.</h5>

<h3>Cevap</h3>
<h6>
</p>1- Binary Search ağacında, ağacın sol tarafına küçük sayı, sağ tarafına ise büyük sayı yazılır.</p>
Root'u 7 olarak kabul edip işlemlerimizi yaparsak; 7, 5'ten büyüktür. O halde 7'nin soluna yazılacaktır. 1, hem 7 hem 5'ten küçüktür. O halde 5'in soluna yazılacaktır. 8, 7'den büyüktür, o halde 7'nin sağ tarafına yazılır. Bu şekilde ilerlersek elde edeceğimiz binary search ağacı aşağıdaki gibi olacaktır:
</h6>

                  7          -> Root 
                 / \
                /   \
               5     8       -> 1. Düğüm
              / \     \
             /   \     \
            1     6     9    -> 2. Düğüm
           / \
          /   \
         0     3             -> 3. Düğüm
              / \
             /   \
            2     4          -> 4. Düğüm