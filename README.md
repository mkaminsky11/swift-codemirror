#Swift + CodeMirror#

###About###
Swift, recently released by Apple, promises to become a more friendly alternative to Objective-C. It that's the case, web-based editors like Ace and CodeMirror will need syntax highlighting for the language.

This is a somewhat crude Swift mode.

###Progress###
Done
<ul>
  <li>Keywords <code>for else var ...</code></li>
  <li>@ - preffixed <code>@lazy var lazy_variable = "lazy..."</code></li>
  <li>Numbers <code>var pi = 3.14159</code></li>
  <li>Comments</li>
  <li>Constants <code>var something = nil</code><li>
  <li>Operators <code>+ - * ...</code></li>
  <li>String</li>
  <li>Variable in a string</li>
  <li>Regex</li>
</ul>

Still to do
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
Result
```
> this is an outer string and inner variable
```

###Demo/Usage###
<img src="swift.gif" alt="screenshot">


Swift mode is being used for <a href="https://codeyourcloud.com">codeyourcloud.com</a>.

Html
```html
<link href=""
```
=======
A demo can be seen <a href="http://mkaminsky11.github.io#code">here</a>.
