Project: Simple Web Application 
===============================

**This simple website that shows a list of applicants for a job. When you click on an applicant's name, it takes you to more information about that candidate, including their name, date of birth and a summary of their work experience.**

- This appliction uses javascript
- It is based upon the GOV.UK frontend toolkit

Build
=====

This project was built directly in github using html, css, and javascript.

The javascript function used to display the applicant information was the onclick event:

   function myFunction1() {
    var x = document.forms["frm1"];
    var text = "";
    var i;
    for (i = 0; i < x.length ;i++) {
        text += x.elements[i].value + "<br>";
    }
    document.getElementById("demo").innerHTML = "You've just clicked on Mathew Jones. Test for onclick javascript function completed!";
    console.log ("event happened")
    
Test
====
Please follow the link to see the test javascript demonstrated:

http://js.do/code/mathewjones



