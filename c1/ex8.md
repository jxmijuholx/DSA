Write a class Person that has a member function hello()

<strong>The output from your program, when called with the code in the Test column, should be exactly as shown in the Result column:<strong>

<table border="1" style="border-collapse: collapse; text-align: left; width: 100%;">
  <thead>
    <tr>
      <th>Testi</th>
      <th>Tulos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        p = Person('Matti')<br>
        p.hello()
      </td>
      <td>Hello, my name is Matti</td>
    </tr>
  </tbody>
</table>

````python
class Person:
    def __init__(self, name):
        self.name = name

    def hello(self):
        print(f"Hello, my name is {self.name}")
````