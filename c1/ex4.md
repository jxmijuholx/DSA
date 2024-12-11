# Sum of the First n Positive Integers

Write a program that takes a positive integer, n, as input and then displays the sum of all of the integers from 1 to n. The sum of the first n positive integers can be computed using the formula:
````m
sum = n * (n + 1)/2
````

<strong>The output from your program, when called with the code in the Test column, should be exactly as shown in the Result column:<strong>
<table border="1" style="border-collapse: collapse; text-align: left; width: 100%;">
  <thead>
    <tr>
      <th>Syöte</th>
      <th>Tulos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>10</td>
      <td>The sum of the first 10 positive integers is 55</td>
    </tr>
    <tr>
      <td>4</td>
      <td>The sum of the first 4 positive integers is 10</td>
    </tr>
  </tbody>
</table>


````python
def sums(n):
    sum = n * (n + 1) // 2
    print(f"The sum of the first {n} positive integers is {sum}")
     
if __name__ == "__main__":
    n = int(input().strip())
    sums(n)
        
````