<html>
<h1>Contact Us</h1>

<form action="https://getform.io/f/3874ed25-7930-49e7-b9f3-88ac060e4db2" method="POST">
    <h2> Name</h2>
    <input type="text" name="name"> <br>
    <h2>Email</h2>
    <input type="email" name="email"><br>
    <h2>Message</h2>
    <input type="text" name="message"><br>
    <!-- add hidden Honeypot input to prevent spams -->
    <input type="hidden" name="_gotcha" style="display:none !important">
    <!-- checkbox handle -->
    <h2>Subscribe</h2><br>
    <input type="checkbox" name="subscribe" value="yes" checked>
    <input type="hidden" name="subscribe" value="no">
    <!-- radio button handle -->
    <h2> What is your budget?</h2>
    <input type="radio" name="budget" value=">1k"> >1k
    <input type="radio" name="budget" value="2-4k"> 2-4k"
    <input type="radio" name="budget" value="4-8k"> 4-8k
    <!-- select field handle -->
    <!-- <select name="work-experience">
        <option value="one-year">0-1 years</option>
        <option value="one-five-years">1-5 years</option>
    </select> -->
    <button type="submit">Send</button>
</form>
</html>