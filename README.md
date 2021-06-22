# python data collection
- Lists
- Tuples
- Dict
- Sets

- Lists (a.k.a Array in other languages)


- Shopping list- multiple items
- add, edit, delete, update
- What is 'crud' -Create, Read, Update and Delete


#### Let's create a shopping list
- Syntax for list is [] - to declare : name_of_list = [" "," "]

shopping_list = ["apples", "eggs", "chocolate", "tea", "bread"]
print(shopping_list)

- Checking the type of data with type()
print(type(shopping_list ))

- How to access chocolate and bread using indexing
print(shopping_list[2])
print(shopping_list[-1])

- Replace an item
shopping_list[0] = "mango"
print(shopping_list)

- How to add an item to shopping list
shopping_list.append("tuna")
print(shopping_list)

 **Task: delete item on index 3 (3 methods)**

-shopping_list.pop(3) # if .pop() will delete last item
-del shopping_list[3]
-shopping_list.remove("tea")

print(shopping_list)

- Lists can have multiple data types
mix_list = [1,2,3,'one','two', 'three']
print(mix_list)

- Tuples and difference betwee lists and tuples
- Syntax () - name_of_tuple = ("","")

essentials = ('paracetamol','milk','butter')
print(type(essentials))
print(essentials)

 **Error: 'turple' object has no attribute error**
essentials.pop(1)
print(essentials)

 **Lists are MUTABLE and tuples are IMMUTABLE!!**


