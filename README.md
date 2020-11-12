#### Task 1
- Declare a list with numbers 1 to 5 and add 6 at the end of the list
```
nlist = [1, 2, 3, 4, 5]
nlist.append(6)
print(nlist)
```
##### Task 2
- Create a tuple with values 1 to 5 then iterate through and print until 3 then stop
```
nums = {1, 2, 3, 4, 5}

for _ in nums:
    if _ > 3:
        break
    print(_)
```

#### Task 3
-  Declare a shopping list dictionary
```
shop_dict = {1:"bread", 2:"bananas", 3:"apples"}
for key, value in shop_dict.items():
    print(f"{key} : {value}")
    print(type(value))
```

##### Task 4
- Replace the price of items in Jake's code
```
jake_shop_list = {"apples":4, "books":6, "bananas":2}
jake_shop_list["apples"] = 3
print(jake_shop_list["apples"])
```

##### Task 5
- Make an add function
```
def add(num1, num2):
    return num1 + num2

print(add(2, 4))
```

#### Task 6
- Create a Person class, with name and age as parameters
```
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
```

#### Task 7
- Create a subclass of Person called Student
```
class Student(Person):
    def __init__(self, name, age, student_id, course):
        super().__init__(name, age)
        self.student_id = student_id
        self.course = course

j = Student("Jared", 21, 123, "DevOps")
print(j.name, j.age, j.student_id, j.course)
```