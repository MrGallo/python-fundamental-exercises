# Web Addresses


Objects are an easier way to create a single variable that
can hold several different values. For example, consider the problem
of storing a mailing address. The address has many parts, but is
conceptually one unit.


## Files Needed

```eval_rst
* :download:`web_addresses.py <examples/web_addresses.py>`
```

The code provided will create an object called `Address` that contains four fields:


1. a field for the house number / street name (a `str`)
2. a field for the city name (a `str`)
3. a field for the state (a `str`)
4. a field for the zip code (an `int`)


Then, the code provided creates a variable to hold an `Address` object and reads the values of the first address from the text file and saves them into the four fields of the object.


It does the same thing for a second and third address. Finally, it
prints out the three addresses on the screen.


What You Should See
-------------------
```
191 Marigold Lane, Miami, FL  33179
3029 Losh Lane, Crafton, PA  15205
4939 Holt Street, Lake Worth, FL  33463
```

What You Should Do on Your Own
------------------------------
Assignments turned in *without* these things will receive no credit.

1. The code provided only creates three `Address` objects. Change the code to read and display two more addresses from the file.

---


©2021 Daniel Gallo


This assignment is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 3.0 United States License](https://creativecommons.org/licenses/by-nc-sa/3.0/us/deed.en_US).  

![Creative Commons License](images/by-nc-sa.png)





Adapted for Python from Graham Mitchell's [Programming By Doing](https://programmingbydoing.com/)