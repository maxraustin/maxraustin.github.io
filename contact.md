# Contact

---

<form id="formaction" method="POST">
<p>Email: </p><input type="email" name="_replyto"><br>
<p>Subject: </p><input type="text" name="subject"><br>
<p>Description: </p><textarea name="description" rows="5"></textarea><br>
<input type="submit" value="Send">
</form>
<br>
<input type="hidden" name="_next" value="thanks.md" />
<input type="text" name="_gotcha" style="display:none" />
<script>
    var contactform = document.getElementById('formaction');
    contactform.setAttribute('action', '//formspree.io/' + 'maxraustin' + '@' + 'gmail' + '.' + 'com');
</script>