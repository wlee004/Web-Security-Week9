Week 9 Project: Pentesting Live Targets

Time Spent: 10 Hours spent in total

<pre>1. Username Enumeration
</pre>

<pre>2. Insecure Direct Object Reference 
RED</pre>
![](insecure_direct_object_reference.gif)

In Find a Saleperson, click on an existing salesperson and in the url set the id attribute to 10, 11, etc. 

<pre>3. SQL Injection
BLUE</pre>
![](sql_injection.gif)

Using SQL injection in blue by trying ' OR 1=1-- we recieve the message "Database query failed." showing that the database changed.

<pre>4. Cross-Site Scripting 
Green</pre>

![](cross_site_scripting.gif)

Using Cross site scripting on the green site by typing <script>alert('WOW found the XSS!')</script> in the feedback and then logging in and click on feedback we can see the pop-up notifications of all the previous feedbacks.

<pre>5. Cross-Site Request Forgery 
RED</pre>

![](cross_site_request_forgery1.gif)

![](cross_site_request_forgery2.gif)

Here we are changing the user's information without the being an admin 

<pre>6. Session Hijacking/Fixation 
</pre>
