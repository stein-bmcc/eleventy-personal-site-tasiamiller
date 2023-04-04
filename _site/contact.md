---
title: Hello? This is Moni.
date: 
layout: base
tags:
  - contact
---
<main id="main">
  <div class="container">
    <div style="text-align:center">
     <h1>Reach Moni</h1>
      <h2>Want To Share Your Mind?</h2>
    </div>
    <div class="row">
      <div class="column">
        <figure>
            <img src="/images/heartphone.jpg" alt="Hand drawn cell phone with hearts" style="width:100%">
            <figcaption>Image by <a href="https://www.freepik.com/free-vector/hand-drawn-conversation-hearts-illustration_21755575.htm#query=anime%20phone&position=18&from_view=search&track=ais">Freepik</a></figcaption>
          </figure> 
      </div>
      <div class="column">
        <form action="/action_page.php" data-netlify="true" data-netlify-recaptcha="true">
          <label for="fname">First Name</label>
          <input type="text" id="fname" name="firstname" placeholder="Your name..">
          <label for="lname">Last Name</label>
          <input type="text" id="lname" name="lastname" placeholder="Your last name..">
          <label for="country">Country</label>
          <select id="country" name="country">
            <option value="usa">United States</option>
            <option value="canada">Canada</option>
            <option value="asia">Asia</option>
          </select>
          <label for="subject">Subject</label>
          <textarea id="subject" name="subject" placeholder="Share your mind?" style="height:170px"></textarea>
          <input type="submit" value="Submit">
        </form>
      </div>
    </div>
  </div> 

</main>
