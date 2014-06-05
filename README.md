#Swift + CodeMirror#
===========
Swift, recently released by Apple, promises to become a more friendly alternative to Objective-C. It that's the case, web-based editors like Ace and CodeMirror will need syntax highlighting for the language.

This is a somewhat crude Swift mode.

Done
<ul>
  <li>Keywords</li>
  <li>@ - preffixed</li>
  <li>Numbers</li>
  <li>Comments</li>
  <li>Constants<li>
  <li>Operators</li>
  <li>String</li>
  <li>Variable in a string</li>
  <li>Regex</li>
</ul>

Stil to do
<ul>
  <li>Indenting</li>
  <li>Autocomplete</li>
</ul>

###Variable in a string###
========
Code
```
var inner_var = "inner variable";
println("this is an outer string and \(inner_var)");
```
Reuslt
```
> this is an outer string and inner variable
```
