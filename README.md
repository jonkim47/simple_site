# ralph_simple_site

Three examples are included:
----------------------------
Registration - is an example of a Segment identify call - https://segment.com/docs/connections/spec/identify/
Product Info Request and Trial Request - are examples of Segment track calls - https://segment.com/docs/connections/spec/track/

Each example consists of a form for user input, once the form's button is pressed a function is executed that sends the associated json to Segment.  The json is visible in the segment javascript source debugger tab.


Wiring it up:
-------------
1) Form - HTML components
2) UI Variables - create variables based on id fields in the form 
3) Listener - Submit button
4) Function - sends data to Segment


![image](https://user-images.githubusercontent.com/104518622/191780417-e23642a7-8aa2-481b-9904-6e2d484ef6ee.png)
