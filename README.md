# Functions2

## Getting started

Run your code

```
    $ python functions.py
```


## Goal

Implement the following functions. 

**Start with the code that tests the method**, then use that code to think about the problem and write your function.

Make a commit after correctly implementing each function.

DO NOT print inside of functions.

1. ###elevenish

    A number is elevenish if it is a multiple of eleven or one greater than a multiple of eleven.
    
    ####Parameters

    <table>
        <th>Name</th>
        <th>Type</th>
        <th>Notes</th>
        <tbody>
            <tr>
                <td>n</td>
                <td><code>int</code></td>
                <td>The number to check</td>
            </tr>
        </tbody>
    </table>

    ####Return
    
    <table>
        <th>Type</th>
        <th>Value</th>
        <tbody>
            <tr>
                <td>boolean</td>
                <td><code>True</code> when <code>n</code> is <strong>elevenish</strong>, <br><code>False</code> otherwise.</td>
            </tr>
        </tbody>
    </table>

    

2. ###ice_cream_party

    You are having a party with amounts of ice cream and candy. Return the int outcome of the party encoded as 0=bad, 1=good, or 2=great. A party is good (1) if both ice cream and candy are at least 5. However, if either ice cream or candy is at least double the amount of the other one, the party is great (2). However, in all cases, if either ice cream or candy is less than 5, the party is always bad (0).

    ####Parameters

    <table>
        <th>Name</th>
        <th>Type</th>
        <th>Notes</th>
        <tbody>
            <tr>
                <td>ice_cream</td>
                <td><code>int</code></td>
                <td>The amount of ice cream at the party</td>
            </tr>
            <tr>
                <td>candy</td>
                <td><code>int</code></td>
                <td>The amount of candy at the party</td>
            </tr>
        </tbody>
    </table>

    ####Return

    <table>
        <th>Type</th>
        <th>Value</th>
        <tbody>
            <tr>
                <td><code>int</code></td>
                <td><strong>0</strong> when the party is <strong>bad</strong><br><strong>1</strong> when the party is <strong>good</strong><br><strong>2</strong> when the party is <strong>great</strong></td>
            </tr>
        </tbody>
    </table>
3. ###successful_squirrel_party

    When squirrels get together for a party, they like to have nuts. A squirrel party is successful when the number of nuts is between 40 and 60, inclusive. Unless it is the weekend, in which case there is no upper bound on the number of nuts. Return true if the party with the given values is successful, or false otherwise.

    ####Parameters

    <table>
        <th>Name</th>
        <th>Type</th>
        <th>Notes</th>
        <tbody>
            <tr>
                <td>nuts</td>
                <td><code>int</code></td>
                <td>The amount of nuts at the party</td>
            </tr>
            <tr>
                <td>is_weekend</td>
                <td><code>boolean</code></td>
                <td><code>True</code> when it is the weekend, <br><code>False</code> during the week</td>
            </tr>
        </tbody>
    </table>

    ####Return

    <table>
        <th>Type</th>
        <th>Value</th>
        <tbody>
            <tr>
                <td><code>boolean</code></td>
                <td><code>True</code> when the party is successful, <br><code>False</code> when it is not</td>
            </tr>
        </tbody>
    </table>
4. ###ticket

    You have a lottery ticket, with ints a, b, and c on it. This makes three pairs, which we'll call ab, bc, and ac. Consider the sum of the numbers in each pair. If any pair sums to exactly 10, the result is 10. Otherwise if the ab sum is exactly 10 more than either bc or ac sums, the result is 5. Otherwise the result is 0.

    ####Parameters

    <table>
        <th>Name</th>
        <th>Type</th>
        <th>Notes</th>
        <tbody>
            <tr>
                <td>a</td>
                <td><code>int</code></td>
                <td>The first number on the ticket</td>
            </tr>
            <tr>
                <td>b</td>
                <td><code>int</code></td>
                <td>The second number on the ticket</td>
            </tr>
            <tr>
                <td>c</td>
                <td><code>int</code></td>
                <td>The third number on the ticket</td>
            </tr>
        </tbody>
    </table>

    ####Return

    <table>
        <th>Type</th>
        <th>Value</th>
        <tbody>
            <tr>
                <td><code>int</code></td>
                <td>A pair sums to 10 => <strong>10</strong> <br>The <strong>ab</strong> sum is greater than others => <strong>5</strong><br>Otherwise => <strong>0</strong></td>
            </tr>
        </tbody>
    </table>
5. ###in_order

    Given three ints, a b c, return true if b is greater than a, and c is greater than b. However, with the exception that if "bOk" is true, b does not need to be greater than a.

    ####Parameters

    <table>
        <th>Name</th>
        <th>Type</th>
        <th>Notes</th>
        <tbody>
            <tr>
                <td>a</td>
                <td><code>int</code></td>
                <td>Any integer</td>
            </tr>
            <tr>
                <td>b</td>
                <td><code>int</code></td>
                <td>Any integer</td>
            </tr>
            <tr>
                <td>c</td>
                <td><code>int</code></td>
                <td>Any integer</td>
            </tr>
            <tr>
                <td>bOK</td>
                <td><code>boolean</code></td>
                <td><code>True</code> when <strong>b</strong> is okay, <code>False</code> when it is not</td>
            </tr>
        </tbody>
    </table>

    ####Return

    <table>
        <th>Type</th>
        <th>Value</th>
        <tbody>
            <tr>
                <td><code>boolean</code></td>
                <td><code>True</code> when <strong>a</strong>, <strong>b</strong>, and <strong>c</strong> are in ascending order, <br> unless <strong>b</strong> is okay then it can be not greater than <strong>a</strong>. <br> <code>False</code> otherwise<br></td>
            </tr>
        </tbody>
    </table>
6. ###less_by_ten

    Given three ints, a b c, return true if one of them is 10 or more less than one of the others.

    ####Parameters

    <table>
        <th>Name</th>
        <th>Type</th>
        <th>Notes</th>
        <tbody>
            <tr>
                <td>a</td>
                <td><code>int</code></td>
                <td>Any integer</td>
            </tr>
            <tr>
                <td>b</td>
                <td><code>int</code></td>
                <td>Any integer</td>
            </tr>
            <tr>
                <td>c</td>
                <td><code>int</code></td>
                <td>Any integer</td>
            </tr>
        </tbody>
    </table>

    ####Return

    <table>
        <th>Type</th>
        <th>Value</th>
        <tbody>
            <tr>
                <td><code>boolean</code></td>
                <td><code>True</code> if one of <strong>a</strong>, <strong>b</strong>, or <strong>c</strong> is <strong>10 or more</strong> less than one of the others, <br> <code>False</code> otherwise<br></td>
            </tr>
        </tbody>
    </table>
7. ###fizz_string

    Given a string s, if the string starts with "f" return "Fizz". If the string ends with "b" return "Buzz". If both the "f" and "b" conditions are true, return "FizzBuzz". In all other cases, return the string unchanged.

    ####Parameters

    <table>
        <th>Name</th>
        <th>Type</th>
        <th>Notes</th>
        <tbody>
            <tr>
                <td>s</td>
                <td><code>str</code></td>
                <td>The <strong>string</strong> to check</td>
            </tr>
        </tbody>
    </table>

    ####Return

    <table>
        <th>Type</th>
        <th>Value</th>
        <tbody>
            <tr>
                <td><code>str</code></td>
                <td><code>"Fizz"</code> when <code>s</code> starts with <strong>f</strong> <br><code>"Buzz"</code> when <code>s</code> ends with <strong>b</strong> <br><code>"FizzBuzz"</code> when both of the above conditions are true <br><code>False</code> in all other situations</td>
            </tr>
        </tbody>
    </table>
8. ###first_last_six
	Given an array of integers, return true if 6 appears as either the first or last element in the array. The array will be length 1 or more.

    ####Parameters

    <table>
        <th>Name</th>
        <th>Type</th>
        <th>Notes</th>
        <tbody>
            <tr>
                <td>list</td>
                <td><code>array</code></td>
                <td>An <strong>array</strong> of integers, <br>the length of which is at least 1</td>
            </tr>
        </tbody>
    </table>

    ####Return

    <table>
        <th>Type</th>
        <th>Value</th>
        <tbody>
            <tr>
                <td><code>boolean</code></td>
                <td><code>True</code> when a <strong>6</strong> is the <strong>first</strong> or <strong>last</strong> element of the list, <br><code>False</code> otherwise</td>
            </tr>
        </tbody>
    </table>
9. ###rotate_left

    Given an array of 3 integers, return an array with the elements "rotated left" so 1, 2, 3 yields 2, 3, 1.

    ####Parameters

    <table>
        <th>Name</th>
        <th>Type</th>
        <th>Notes</th>
        <tbody>
            <tr>
                <td>trio</td>
                <td><code>array</code></td>
                <td>An <strong>array</strong> of 3 integers</td>
            </tr>
        </tbody>
    </table>

    ####Return

    <table>
        <th>Type</th>
        <th>Value</th>
        <tbody>
            <tr>
                <td><code>array</code></td>
                <td>A version of <code>trio</code> with the numbers <strong>rotated left</strong> one place</td>
            </tr>
        </tbody>
    </table>
10. ###double23

    Given an integer array, return true if the array contains 2 twice, or 3 twice. The array will have 0, 1, or 2 elements.

    ####Parameters

    <table>
        <th>Name</th>
        <th>Type</th>
        <th>Notes</th>
        <tbody>
            <tr>
                <td>nums</td>
                <td><code>array</code></td>
                <td>An <strong>array</strong> of integers, <br>which will always have 0, 1, or, 2 elements</td>
            </tr>
        </tbody>
    </table>

    ####Return

    <table>
        <th>Type</th>
        <th>Value</th>
        <tbody>
            <tr>
                <td><code>boolean</code></td>
                <td><code>True</code> when <code>nums</code> contains <strong>2 twice</strong> or <strong>3 twice</strong>, <br><code>False</code> otherwise</td>
            </tr>
        </tbody>
    </table>