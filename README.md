 <h1>Python Tuples Documentation</h1>

<p><strong>Overview</strong></p>
<p>A <strong>tuple</strong> is a built-in data type in Python that is used to store a collection of ordered, immutable elements. Tuples are similar to lists but with one key difference: <strong>tuples cannot be modified once they are created</strong>. They are hashable, meaning they can be used as keys in dictionaries, unlike lists.</p>

<h2>Table of Contents</h2>
    <ul>
        <li><a href="#creating-tuples">Creating Tuples</a></li>
        <li><a href="#accessing-tuple-elements">Accessing Tuple Elements</a></li>
        <li><a href="#slicing-a-tuple">Slicing a Tuple</a></li>
        <li><a href="#tuple-methods">Tuple Methods</a></li>
        <li><a href="#tuple-packing-and-unpacking">Tuple Packing and Unpacking</a></li>
        <li><a href="#use-cases">Use Cases</a></li>
    </ul>

  <h2 id="creating-tuples">Creating Tuples</h2>
    <p>Tuples are created by placing elements inside <code>parentheses ()</code>, separated by commas.</p>
    <div class="example">
        <p><strong>Examples:</strong></p>
        <ul>
            <li>A tuple with integers: <code>(1, 2, 3, 4)</code></li>
            <li>A tuple with mixed data types: <code>(1, "Hello", 3.14, [1, 2, 3])</code></li>
            <li>A tuple with one element (note the trailing comma): <code>(5,)</code></li>
        </ul>
    </div>

  <h2 id="accessing-tuple-elements">Accessing Tuple Elements</h2>
    <p>You can access individual elements from a tuple using <strong>indexing</strong>. Python uses zero-based indexing, so the first element is at index <code>0</code>.</p>
    <div class="example">
        <p><strong>Example:</strong></p>
        <ul>
            <li>To access the first element: <code>my_tuple[0]</code></li>
            <li>To access the last element: <code>my_tuple[-1]</code></li>
        </ul>
    </div>

  <h2 id="slicing-a-tuple">Slicing a Tuple</h2>
    <p>You can <strong>slice</strong> tuples similarly to lists. Slicing allows you to extract a subset of elements from the tuple.</p>
    <div class="example">
        <p><strong>Example:</strong></p>
        <ul>
            <li>To slice from index 1 to index 3 (excluding index 3): <code>my_tuple[1:3]</code></li>
        </ul>
    </div>

  <h2 id="tuple-methods">Tuple Methods</h2>
    <p>Tuples are immutable, so they don’t have many methods. However, they do have a few useful ones:</p>
    <ul>
        <li><strong>count(value)</strong> – Returns the number of times a specified value appears in the tuple.</li>
        <li><strong>index(value)</strong> – Returns the index of the first occurrence of a specified value.</li>
    </ul>

  <h2 id="tuple-packing-and-unpacking">Tuple Packing and Unpacking</h2>
    <h3>Tuple Packing:</h3>
    <p>Tuples can be packed by grouping multiple values into a single variable.</p>

  <h3>Tuple Unpacking:</h3>
    <p>You can assign the elements of a tuple to multiple variables in one line.</p>

  <h2 id="use-cases">Use Cases</h2>
    <h3>1. Immutability</h3>
    <p>When you need an ordered collection that should not be modified, such as a constant set of values (e.g., coordinates, RGB values).</p>

  <h3>2. Dictionaries</h3>
    <p>Tuples can be used as keys in dictionaries, unlike lists which are mutable and not hashable.</p>

</body>
</html>
