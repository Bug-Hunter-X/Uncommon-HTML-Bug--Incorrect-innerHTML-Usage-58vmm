# Uncommon HTML Bug: Incorrect innerHTML Usage

This repository demonstrates an uncommon bug related to the use of `innerHTML` in HTML.  The bug arises from attempting to insert a JavaScript object directly into the DOM using `innerHTML`. This results in a type error because `innerHTML` expects a string, not an object.

The solution involves correctly converting the JavaScript object to a string before inserting it into the DOM, for example, using JSON.stringify().