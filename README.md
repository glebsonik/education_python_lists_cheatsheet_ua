
Шпаргалка по Python
===============================

Lists
----
```python
names = ["Andrii", "Jack", "Bob"] # Наш список імен
len(names)                        # Поверне 3, кількість елементів
names.index("Jack")               # Поверне 1, тобто порядковий номер
names[2]                          # Поверне Bob, тобто третій елемент з нульового
names[-1]                         # Поверне Bob (рахуємо з кінця)
names[-2]                         # Поверне Jack (рахуємо з кінця)
names.insert(1, "John")           # Додасть імʼя John на вказаний індекс
print(names)                      # Виведе ["Andrii", "John", "Jack", "Bob"]

names.append("Billy") # Додасть Billy у кінець списка
print(names) # Виведе ["Andrii", "John", "Jack", "Bob", "Billy"]

names.reverse() # Розверне список
print(names) # Виведе ["Billy", "Bob", "Jack", "John", "Andrii"]

names.sort() # Відсортує масив, у алфавітному порядку
print(names) # Виведе ["Andrii", "Billy", "Bob", "Jack", "John"]

names.append("Bob") # додасть ще один Bob у кінець
print(names) # Виведе ["Andrii", "Billy", "Bob", "Jack", "John", "Bob"]
names.count("Bob") # поверне 2, порахує кількість імен "Bob"

names.remove("Bob") # видалить перше знайдене імʼя Bob
print(names) # Виведе ["Andrii", "Billy", "Jack", "John", "Bob"]

print("Jack" in names) # поверне True, in перевіряє чи є елемент у списку

names.extend(["Olya", "Serge"]) # Розширить список ще двома іменами Olya і Serge
print(names) # поверне ["Andrii", "Billy", "Jack", "John", "Bob", "Olya", "Serge"]

# Або extend можна замінити використовуючи додавання
names_1 = ["Andrii", "Billy", "Jack", "John", "Bob"]

names_2 = names_1 + ["Olya", "Serge"]
print(names_2) # поверне ["Andrii", "Billy", "Jack", "John", "Bob", "Olya", "Serge"]

names_2.clear() # Повністю очистить список
print(names_2) # Поверне [], тобто порожній список
```

```python
# Список з числами
numbers = [1,2,25,3] # Наш список з числами
min(numbers) # поверне 1
max(numbers) # Поверне 25
sum(numbers) # Поверне 31
```
