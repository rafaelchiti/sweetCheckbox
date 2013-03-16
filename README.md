# sweetCheckbox



jQuery plugin simulating a switch component but using the standard html checkbox WITHOUT any special API or crazy methods to check or uncheck them.

## What?
- Why another plugin for simulating a checkbox?
 - First because we needed this particular style and components/plugins outside were to complex for styling.
 - Second, we only needed a nice style not a complex and huge API or methods with lot of configuration. And the most important we wanted to stick to the way that a checkbox behave, instead of calling special API methods for checking it or unchecking it.
- After styling the checkbox you will continue to have an input type checkbox on your html, it will be submitted when sending a form and do all the common
things a checkbox would do. You can trigger a click on the checkbox and the plugin will update the styled checkbox as well, so you don't need to call a method on the plugin to interact with the checkbox.


## How?

Simple, just add your checkbox to your html like you would usually do: 
```html 
<input type="checkbox"> 
```

Then call the plugin over the elements you want to apply the style.

```javascript
$('input[type=checkbox]').sweetCheckbox();
```

Thats it!.

## Settings
We added some standard settings, like size, selector, etc. For a full list check the 
[wiki (still in progress, so far you can check the source that it's well documented, sorry!)]().
If you need any other configuration setting just let us know, add a ticket on GH issues and we'll check it out.

## Demo

[Check it out here](http://rafaelchiti.github.com/sweetCheckbox/)
