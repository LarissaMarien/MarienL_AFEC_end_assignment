---
layout: page.njk
title: Contact me
tags:
  - nav
---

## {{title}}

<form action="#">
    <h1> Contact me here</h1>  
    <label for="naam">Your name:</label>  
    <input type="text" name= "naam" id="naam">
    <label for="emailadres">Your e-mail adress:</label>
    <input type="email" name="emailadres" id="emailadres">
    <label for="message">Your message to me:</label>
    <input type="message" name="message" id="message">
    <label for="reason">Reason for message:</label>
    <select name="reason" id="reason">
      <option value="shoutout">Shoutout</option>
      <option value="question">Question</option>
      <option value="complaint">Complaint</option>
      <option value="other">Other</option>
    </select>
    <input type="submit" name="send" value="SEND">
</form>
