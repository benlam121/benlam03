---
layout: layout.html
---
## Contact us.

<p>The following form is using FormSubmit.co.</p>
<style>
  #workemail {display: none;}
</style>
<form action="https://formsubmit.co/benlam263187042@gmail.com" method="post">
  <p>
    <label>Name:
      <input type="text" name="name">
    </label>    
  </p>
  <p>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">    
    <input type="email" id="workemail" name="_honey">
  </p>
  
  
  
  <p>The following form is using Netlify form.</p>
  <p>
    <label for="content">Content:</label>
    <textarea name="content" id="content"></textarea>
  </p>
  <input type="hidden" name="_next" value="https://demo-20200516.netlify.app/thanks">
  <input type="hidden" name="_captcha" value="false">
  <input type="submit" value="Send Form">
</form>
<form name='contact' method='POST' enctype='multipart/form-data'><input type='hidden' name='form-name' value='contact' />
  <p>
    <label>
      Your Name: 
      <input type="text" name="name" />
    </label>   
  </p>
  <p>
    <label>
      Your Email: 
      <input type="email" name="email" />
    </label>
  </p>
  <p>
    <label>
      Message: 
      <textarea name="message"></textarea>
    </label>
  </p>
  <p>
    <label>
      Attachment:
      <input type="file" name="attachment" multiple>
    </label>
  </p>
  <p>
    <input type="submit" value="Send">
  </p>
</form>
