# Frontend-homework rubaxa
1. __Implement creation of the following record:__ [Roman](https://github.com/Gokert/Frontend-homework-rubaxa/blob/main/tasks/romanNums.js)


    ```
    console.log(0..V); // [0, 1, 2, 3, 4];
    console.log(0..VII); // [0, 1, 2, 3, 4, 5, 6];
    ```

2. __Is it possible to realize this?__ [a-lt-a](https://github.com/Gokert/Frontend-homework-rubaxa/blob/main/tasks/a-lt-a.js)
    ```
    var a;

    console.log(a == a); // true
    console.log(a < a); // true
    ```

3. __Modify a regular expression based on an existing one (without copy-paste)__ [regexp](https://github.com/Gokert/Frontend-homework-rubaxa/blob/main/tasks/regexp.js)
    ```
    var r_09 = /[0-9]+/;
    var r_sign = /[-+]/;
    var r_sign09 = /^$/; // modify using r_sign and r_09


    console.log(r_sign09.test('0')); // true
    console.log(r_sign09.test('-123')); // true
    console.log(r_sign09.test('+345')); // true
    console.log(r_sign09.test('123+345')); // false
    console.log(r_sign09.test('345+')); // false
    console.log(r_sign09.test('x123')); // false
    ```
    
4. __Implement the `size` property for all arrays, which would work exactly the same as `length`.__ [array.size](https://github.com/Gokert/Frontend-homework-rubaxa/blob/main/tasks/array.size.js)
    ```
    console.log([0, 1].size); // 2

    var arr = [0, 1, 2];
    arr.size = 0;
    console.log(arr); // []
    ```

5. __Implement RLE compression: AAAB -> A3B, BCCDDDAXXXX -> BC2D3AX4__ [rle](https://github.com/Gokert/Frontend-homework-rubaxa/blob/main/tasks/rle.js)
    ```
    function rle(value) {
    }


    console.log(rle('AVVVBBBVVXDHJFFFFDDDDDDHAAAAJJJDDSLSSSDDDD'));
    ```
    