#selection-sort

<h3>Sorular</h3>
<h5>[22,27,16,2,18,6] -> Insertion Sort</h5>

<h6>1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2- Big-O gösterimini yazınız.

3- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

*Average case: Aradığımız sayının ortada olması
*Worst case: Aradığımız sayının sonda olması
*Best case: Aradığımız sayının dizinin en başında olması.

4- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.</h6>

<h3>Cevaplar</h3>


<ol>
    <li>
        <ul>
            <li>
            <h5>[2,27,16,22,18,6] => Dizinin en küçük sayısı olan 2, en başa gelir. 22 ile yer değiştirir.</h5>
            </li>
            <li><h5>
                [2,6,16,22,18,27] => Dizinin en küçük ikinci sayısı olan 6, 2'nin hemen ardından ikinci ıraya yerleşir. 27 ile yer değiştirir.</h5>
            </li>
                <li><h5>
                [2,6,16,18,22,27] => Üçüncü eleman ilk 2 elemandan sonraki en küçük sayı olduğundan değişiklik yapılmaz ve sıralamanın doğru olması için 18 ve 22 yer değiştirir.</h5>
            </li>
        </ul>
    </li>
    <br>
    <li><h5>
        n + (n-1) + (n-2) + (n-3) + (n-4) + 1 = n(n+1)/2 kadar işlem yapılır. (n^2+n)/2 Big-O gösterimidir.</h5>
    </li>
    <br>
    <li><h5>
        Bulunması istenilen eleman, dizinin ortasında bulunmaktadır. Bu sebeple 18 sayısı Average Case kapsamına girer.</h5>
    </li>
    <br>
    <li>
        <ul><h5>[7,3,5,8,2,9,4,15,6]</h5>
            <li>
                <h5>[2|3, 5, 8, 7, 9, 4, 15, 6]</h5>
            </li>
            <li>
                <h5>[2, 3|5, 8, 7, 9, 4, 15, 6]</h5>
            </li>
            <li>
                <h5>[2, 3, 4|7, 9, 5, 15, 6]</h5>
            </li>
            <li>
                <h5>[2, 3, 4, 5, 7, 9, 8, 15, 6]</h5>
            </li>
        </ul>
    </li>
</ol>