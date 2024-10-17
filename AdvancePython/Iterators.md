Iterators are advanced Python concepts that allow for efficient looping and memory managment. Iterators provide a way to access elements of a collection sequentially without exposing the underlying structure.
<pre><code>
my_list = [1,2,3,4,5,6]
for i in my_list:
   print(i)
</code></pre>

-->  iter keyword
<pre><code>
iterator=iter(my_list)
print(type(iterator))
</code></pre>
--- it uses lazy loading
<pre><code>
next(iterator)
</code></pre>
--> it shows one by one when we execute next to next

<pre>
   <code>
iterator = iter(my_list)
      try:
        next(iterator)
      except StopIteration:
        print("there are no elements in the iteraror")
   </code>
</pre>

String Iterators :
<pre>
   <code>
my_string = "Hello"
string_iterator = iter(my_string)
print(next(string_iterator)    #H
print(next(string_iterator)    #e
   </code>
</pre>





