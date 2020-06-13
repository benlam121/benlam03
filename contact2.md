---
layout: layout.html
---
## Contact us
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
