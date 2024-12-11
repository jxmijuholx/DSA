# Sum a Collection of Numbers

Write a program that sums all of the numbers taken as input, while ignoring any input that is not a valid number.
Your program should display the current sum after each number is entered. It should display an error message after each non-numeric input, and then continue to sum any additional numbers entered by the user.  The program exits when the user enters 0. 
Ensure that your program works correctly for both integers and floating-point numbers.

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
      <td>12<br>6<br>11<br>0</td>
      <td>
        The total is now 12.0<br>
        The total is now 18.0<br>
        The total is now 29.0<br>
        The grand total is 29.0
      </td>
    </tr>
    <tr>
      <td>200<br>hello<br>10<br>0</td>
      <td>
        The total is now 200.0<br>
        That wasn’t a number.<br>
        The total is now 210.0<br>
        The grand total is 210.0
      </td>
    </tr>
  </tbody>
</table>


````python
def sum_numbers():
    total = 0.0
    while True:
        try:
            user_input = input().strip()
            if user_input == '0':
                break
            num = float(user_input)
            total += num
            print(f"The total is now {total:.1f}")
        except ValueError:
            print("That wasn’t a number.")
    
    print(f"The grand total is {total:.1f}")

if __name__ == "__main__":
    sum_numbers()
````