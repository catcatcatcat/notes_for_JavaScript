# Arrays

####codecademy 3-9 Meet Arrays

1. store lists of data
2. can store different data types at the same time
3. are ordered so the position of each piece of data is fixed
    
    
* Syntax:   
**var arrayName = [data, data, data];**   
Any time you see data surrounded by [ ], it is an array.

舉例：
var Catx4 = ["cat1", "cat2", "cat3", "cat4"];

如果想顯示其中某項，比如想顯示第三隻貓是哪隻貓，
可以用`Catx4[2]`來顯示，為什麼第三隻貓寫成[2]呢？
因為陣列開頭是從 0 開始數的。


####codecademy 3-11 Loops & arrays I 

For arrays, a useful way to systematically access every element in the array is to use a for loop!

How does it work?

```
var cities = ["Melbourne", "Amman", "Helsinki", "NYC"];

for (var i = 0; i < cities.length; i++) {
    console.log("I would like to visit " + cities[i]);
}
```

1. Line 3 declares the array. It has 4 elements.
2. We then start the `for` loop on line 5.
3. We see `i` starts off at value 0. 
4. The `for` loop runs until `i < 4` (because `cities.length` equals 4. The array cities has 4 elements in it; see the Hint for more.)
5. We will increment i by 1 each time we loop over.
6. We print out `cities[0]`, which is "Melbourne".
7. We then start the loop again. Except now `i = 1`. 
8. It will print out `cities[1]`, which is "Amman". 
9. This continues until i is no longer less than cities.length.



