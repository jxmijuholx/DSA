# Custom encoder

Write a function called "custom_encoder" that accepts a string text as parameter and for each char of the text it calculates its 0-based position in the following reference string:
````
reference_string = 'abcdefghijklmnopqrstuvwxyz'
````
<strong>The function should return a list that contains all the positions. If a char is not found in the reference_string, its position should be -1<strong>
````
def custom_encoder(string):
    reference_string = 'abcdefghijklmnopqrstuvwxyz'
    list = []
    for c in string:
        index = reference_string.find(c.lower())
        list.append(index)
    return list
        
````