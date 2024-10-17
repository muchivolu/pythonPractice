Iterators are advanced Python concepts that allow for efficient looping and memory managment. Iterators provide a way to access elements of a collection sequentially without exposing the underlying structure.

my_list = [1,2,3,4,5,6]
for i in my_list:
   print(i)

-->  iter keyword
iterator=iter(my_list)
print(type(iterator))

--- it uses lazy loading
next(iterator)

--> it shows one by one when we execute next to next


