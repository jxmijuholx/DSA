# Restaurant

Make a class called Restaurant. The __init__() method for Restaurant should store two attributes: a restaurant_name and a cuisine_type. Make a method called describe_restaurant() that prints these two pieces of information, and a method called open_restaurant() that prints a message indicating that the restaurant is open.

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
        restaurant = Restaurant('Kotipizza', 'pizza')<br>
        print(restaurant.name)<br>
        print(restaurant.cuisine_type)<br>
        restaurant.describe_restaurant()<br>
        restaurant.open_restaurant()
      </td>
      <td>
        Kotipizza<br>
        pizza<br>
        Kotipizza serves wonderful pizza<br>
        Kotipizza is open. Come on in!
      </td>
    </tr>
  </tbody>
</table>

````python
class Restaurant:
    def __init__(self, restaurant_name: str, cuisine_type: str):
        self.name = restaurant_name
        self.cuisine_type = cuisine_type

    def describe_restaurant(self):
        print(f"{self.name} serves wonderful {self.cuisine_type}.")

    def open_restaurant(self):
        print(f"{self.name} is open. Come on in!")
````