<details open><summary><strong>Python 2 or Python 3?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;Python 3.6 (Except for Dataclasses that require version 3.7)
</details><br>

<details open><summary><strong>What is the best way to use it?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;I keep the text file open on separate desktop at all times. It is also in a different text editor than the one I usually use, so it's easier to switch to with <code>Ctrl+↹</code> / <code>⌘↹</code>. Cheatsheet consists of minimal text and short examples so things are easy to find with <code>Ctrl+F</code> / <code>⌘F</code>.<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;I also keep the Python console open at all times to test a little snippets of code, to check out the available functions of a module using code completion and above all, to use <code>help(&lt;module/object/function/type&gt;)</code> command. If something is still unclear, then I search the Python docs by googling <code>'python docs &lt;module/function&gt;'</code>.
</details><br>

<details open><summary><strong>Why the '&lt;type&gt;' semantics?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;It makes examples much less ambiguous.
</details><br>

<details open><summary><strong>Why are some basics like <code>'&lt;list&gt; = [1, 2, 3]'</code> and <code>'&lt;el&gt; = &lt;list&gt;[&lt;int&gt;]'</code> missing?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;This cheatsheet is not intended for complete beginners. This way it can save some valuable space. Nonetheless it tries to be simple enough to be useful for somebody who completed the introductory course.
</details><br>

<details open><summary><strong>What exactly is <code>&lt;el&gt;</code>?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;El is short for element and can be any object, but it usually denotes an object that is an item of a collection.
</details><br>

<details open><summary><strong>What exactly is <code>&lt;collection&gt;</code>?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;Collection is my name for an iterable object. An iterable object in Python is an object that has at least one of iter() and getitem() special methods defined. <code>&lt;el&gt;.__iter__()</code> returns an iterator and <code>&lt;el&gt;.__getitem__(&lt;index&gt;)</code> returns an item at that index. I chose not to use the name iterable because it sounds scarier and more vague than collection, even though it has a precise definition.<br><br>

&nbsp;&nbsp;&nbsp;&nbsp;<code>&lt;iterable&gt;</code> and <code>&lt;collection&gt;</code> should not be confused with abstract base classes collections.abc.Iterable and collections.abc.Collection. Expression <code>instanceof(&lt;object&gt;, Iterable)</code> only checks if object has iter() special method and <code>instanceof(&lt;object&gt;, Collection)</code> checks for len(), iter() and contains().
</details><br>

<details open><summary><strong>What about PEP 8?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;Check out <a href="https://google.github.io/styleguide/pyguide.html">Google Style Guide</a> and use <code>Ctrl+Alt+L</code> / <code>⌥⌘L</code> shortcut in PyCharm to automatically reformat code.
</details><br>

<details open><summary><strong>Why are import statement, virtual environment, tests, packaging and installation not covered?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;Maybe they will be in the future, or I will make a separate cheatsheet about features important for the production.
</details><br>

<details open><summary><strong>Why is Asyncio not covered?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;It's coming soon.
</details><br>

<details open><summary><strong>Why are there no concrete Regex examples?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;Same reason as why are there no SQL examples; They are both separate technologies that are independent from Python and both have a ton of resources available online.
</details><br>

<details open><summary><strong>Why is there no old style string formating?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;Because it's redundant and I don't want to encourage its use.
</details><br>

<details open><summary><strong>Why is staticmethod not covered in Class section?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;Because it's of very limited use and is easy to mix up with classmethod.
</details><br>

<details open><summary><strong>Why are descriptors not covered?</strong></summary><br>
&nbsp;&nbsp;&nbsp;&nbsp;Because property is sufficient for everyday use.
</details><br>