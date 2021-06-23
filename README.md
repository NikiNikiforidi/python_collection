# python data collection
- Lists
- Tuples
- Dict
- Sets

- Lists (a.k.a Array in other languages)


- Shopping list- multiple items
- add, edit, delete, update
- What is 'crud' -Create, Read, Update and Delete


### Let's create a shopping list
- Syntax for list is [] - to declare : name_of_list = [" "," "]

```
shopping_list = ["apples", "eggs", "chocolate", "tea", "bread"]
print(shopping_list)
```

- Checking the type of data with type()
```
print(type(shopping_list))
```

- How to access chocolate and bread using indexing
```
print(shopping_list[2])
print(shopping_list[-1])
```

- Replace an item
```
shopping_list[0] = "mango"
print(shopping_list)
```
- How to add an item to shopping list
```
shopping_list.append("tuna")
print(shopping_list)
```

 **Task: delete item on index 3 (3 methods)**

```
shopping_list.pop(3) # if .pop() will delete last item
del shopping_list[3]
shopping_list.remove("tea")

print(shopping_list)
```

- Lists can have multiple data types
```
mix_list = [1,2,3,'one','two', 'three']
print(mix_list)
```
- Tuples and difference betwee lists and tuples
- Syntax () - name_of_tuple = ("","")
```
essentials = ('paracetamol','milk','butter')
print(type(essentials))
print(essentials)
```
 **Error: 'turple' object has no attribute error**
```
essentials.pop(1)
print(essentials)
```
 **Lists are MUTABLE and tuples are IMMUTABLE!!**

## Dictionaries and Sets
#### Dictionaries and Sets are both data collection
- What are Dictionary and Sets?
- Dictionary: Can manage data but can be more dynamic

- Dictionaries work as KEY and VALUE
- KEY = The reference of the object
- VALUE: What the data storage mechanism wish to use
- Dynamic because we can have Lists, and dict inside a dict
- Syntax - name_of_dict = {}
  -    (key ^) =(value^)

```
student_1 = {
    "Name" : "Niki",
    "Stream" : "DevOps",
    "Completed_lessons" : 4,
    "Completed_lessons_names" : ["Data types","Git and Github","Operators"],
    } # Indexing of List inside Dict is same and begins with 0
```

- Testing Dict and displaying the type
```
print(student_1)
print(type(student_1))
```


- To find a VALUE saved in a specific KEY, use the below syntax.
```
print(student_1["Stream"])
print(student_1["Completed_lessons_names"]) # Will print the whole list
```

- Syntax to pull out a specific VALUE in a list from a specific KEY
```
print(student_1["Completed_lessons_names"][0])
```

 **TASK: Print the second last index of KEY Completed_lessons_names:[]**
```
print(student_1["Completed_lessons_names"][-2])
print(student_1["Completed_lessons_names"][1])
```

**Can we apply CRUD on a Dict?**

-  How to change specific VALUE
```
student_1["Completed_lessons"] =3
print(student_1["Completed_lessons"])
```

- How to remove specific VALUE
```
student_1["Completed_lessons_names"].remove("Operators")
print(student_1["Completed_lessons_names"])
```

- Built in methods to use with Dict
    - To print all KEYS keys()
    - To print all VALUES values()
```
print(student_1.keys())
print(student_1.values())
```

- Sets are also Data collection
 - Syntax name = {"", "", ""}
 - The difference between Dicts and Sets. 
```
shopping_list = ["eggs","tea", "milk"]
```
- Indexing        0       1      2
```
car_parts = {"Engine","Wheels", "Windows"} # Sets are unordered
print(car_parts)
```
-  Adding and removing from Sets
```
car_parts.add("Seats")
car_parts.discard("Wheels")
print(car_parts)
```





