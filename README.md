# 3_8 programming coding standard

##3_8 is a linting standard suggested to be used in any programming language (it was meant to be for php projects only at the start)


It solves many common problems with naming convetions of functions and more.


Its purpose is to be that every function name should have same naming convention across all programming languages, so one fullstack deveoper will not have problem switching f.e. from php to JS

##Reason:


Have you ever asked yourself or colleague what is the name of the function in your project for getting user data? Or what name you should give to function for setting user's name? I believe lot of us did. Is it getUser or getuser or getUserinfo or get_userinfo?


When using 3_8 it's always clear.

##Syntax


Rules for 3_8 naming convention (as name suggests) of function names are:


1. all characters used are lowercase letters chars [a-z], except 4th character, which is always char _ (underscore)


2. It must start with 3 (three) characters
3. It must end with 8 (eight) characters

Variations


Variations like 3_7 or 4_8 was made by some crazy developers, but many real time projects proved 3_8 to be the only valid choice



##Examples:

PHP:
```php

$userData = get_userdata();


$user->set_username($name);


If ($user->has_birthday()) {


  run_birthday();


}
```


```javascript
Javascript (ES6):


const get_userdata = () => {


// get user data


}
```

```css
<article class="row_verywide">

<div id="top_messages">
```
