//need custom theme to change the defaullt documentation format//
<!-- .vitepress/theme/Contact.vue -->
<template> 
  

<h1>Contact Us</h1>

<form action="https://getform.io/f/3874ed25-7930-49e7-b9f3-88ac060e4db2" method="POST">
    <input type="text" name="name">
    <input type="email" name="email">
    <input type="text" name="message">
    <!-- add hidden Honeypot input to prevent spams -->
    <input type="hidden" name="_gotcha" style="display:none !important">
    <!-- checkbox handle -->
    <input type="checkbox" name="subscribe" value="yes" checked>
    <input type="hidden" name="subscribe" value="no">
    <!-- radio button handle -->
    <input type="radio" name="budget" value=">1k" checked>
    <input type="radio" name="budget" value="2-4k">
    <input type="radio" name="budget" value="4-8k">
    <!-- select field handle -->
    <!-- <select name="work-experience">
        <option value="one-year">0-1 years</option>
        <option value="one-five-years">1-5 years</option>
    </select> -->
    <button type="submit">Send</button>
</form>

  <!-- this is where markdown content will be rendered -->
  <Content />
</template>
