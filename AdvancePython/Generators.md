**Generators:**
Generators are a simpler way to create iterators. They use the "yield" keyword to produce a series of values lazily, which means they generate values on the fly and do not store them in memory.
it is subclass for iteraters.
<pre><code>
def square(n):
   for i in range(3):
       return i**2
</code></pre>

in genertors, we need to use "yield" instead of "return".
<pre><code>
def square(n):
   for i in range(3):
       yield i**2
</code></pre>
<br>
Example :
<pre><code>
def my_generator():
   yield 1
   yield 2
   yield 3

gen=my_generator()
gen
next(gen)
</code></pre>
