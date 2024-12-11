# Count vowels

Assume s is a string of lower case characters.
Write a program that counts up the number of vowels contained in the string s. Valid vowels are: 'a', 'e', 'i', 'o', and 'u'.

For example, if s = 'hello', your program should print:

Number of vowels: 2

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
      <td>Restaurant</td>
      <td>Number of vowels: 4</td>
    </tr>
    <tr>
      <td>Air</td>
      <td>Number of vowels: 2</td>
    </tr>
  </tbody>
</table>

````python
def countvowels(string):
    vowels = {'a', 'e', 'i', 'o', 'u'}
    count = 0 
    for c in string.lower():
        if c in vowels:
            count += 1
    print(f"Number of vowels: {count}")
                
if __name__ == "__main__":
    n = input().strip()
    countvowels(n)
    
````