---
title: "Contact me"
template: "page"
socialImage: "/media/me-2.jpg"
---
<!-- <form name="contact" method="POST" data-netlify="true">
  <input type="hidden" name="form-name" value="contact" />
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>

 -->
<form name="contact" method="POST" data-netlify="true">   
  <input type="hidden" name="form-name" value="contact" />
  <input name="name" type="text" class="feedback-input" placeholder="Name" />   
  <input name="email" type="email" class="feedback-input" placeholder="Email" />
  <textarea name="text" class="feedback-input" placeholder="Message"></textarea>
  <input type="submit" value="Send"/>
</form>

<style>

form { 
  max-width:420px; 
  margin:50px auto; 
}

.feedback-input {
  font-family: Helvetica, Arial, sans-serif;
  font-weight:500;
  font-size: 18px;
  border-radius: 5px;
  line-height: 22px;
  background-color: transparent;
  border:2px solid #657b83;
  transition: all 0.3s;
  padding: 13px;
  margin-bottom: 15px;
  width:100%;
  box-sizing: border-box;
  outline:0;
}

.feedback-input:focus { 
  border:2px solid #F7A046; 
}

textarea {
  height: 150px;
  line-height: 150%;
  resize:vertical;
}

[type="submit"] {
  font-family: 'Montserrat', Arial, Helvetica, sans-serif;
  width: 100%;
  background:#657b83;
  border-radius:5px;
  border:0;
  cursor:pointer;
  color:white;
  font-size:24px;
  padding-top:10px;
  padding-bottom:10px;
  transition: all 0.3s;
  margin-top:-4px;
  font-weight:700;
}

[type="submit"]:hover { 
  background:#F7A046; 
}
</style>

