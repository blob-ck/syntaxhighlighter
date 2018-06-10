# syntaxhighlighter
blogger source code - syntax highlighter
# syntaxhighlighter
blogger source code - syntax highlighter


In order to choose the appropriate brush, following are the various brush aliases supporting the corresponding code highlighting:
actionscript3
bash, shell
c-sharp, csharp
cpp, c
css     
delphi, pas, pascal
diff, patch
groovy 
js, jscript, javascript
java
jfx, javafx
perl, pl
php 
plain, text
ps, powershell 
py, python
rails, ror, ruby
scala
sql
vb, vbnet
xml, xhtml, xslt, html, xhtml 

Above aliases can be used at: class="brush: alias" while embedding your code in the Blog.

Another easy way supported by SyntaxHighlighter is to enclose the code within:


* 사용법 - html편집모드에서
```
<pre class="brush: 사용할언어">
#########YOUR CODE########
</pre>
```


The only catch involved out here is, you have to use encoded HTML while embedding within `<pre>`tags.
Your code can be converted to HTML Encoded using following easy to use Tool:
http://www.string-functions.com/htmlencode.aspx

Just copy paste your code & generate the encoded HTML Code. Paste the encoded HTML within `<pre>`tags for correct rendering. Failure to do so might render wrong code, especially < & > brackets.
