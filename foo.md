---
layout: default
---
<p><a href="index.html">Home</a>
<a href="foo.html">foo</a></p>
<h1>Rimu Header One</h1>
<p>This is index.md.</p>
<p>This is line four.<br>
This is line five.<br>
This is line six.<br></p>
<pre class="no-highlight"><code>This is it.
And so is this.</code></pre>
<p>Rimu Preprocessing</p>
<pre class="no-highlight"><code>f=foo; ~/.npm-global/bin/rimuc --output ../$f.md ../_includes/ymlDefault.html $f.rmu</code></pre>
<p>The processed rimu content needs to be on the github server.</p>
<p>It would be good to do the same with asciidoc.
I have asciidoc installed on the jekyll server, so can use asciidoc in the same way.
The _rimu folder can be generalized to _pre.</p>