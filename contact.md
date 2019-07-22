# Contact

---

If you would like to get in contact with me, please fill out and submit the form below, and I'll get to it as soon as I can.

<form id="formaction" method="POST">
	<label for="emailID">Email: </label><br>
	<input type="email" name="_replyto" id="emailID"><br>
	<p>Subject: </p><input type="text" name="subject"><br>
	<p>Description: </p><textarea name="description" rows="10" cols="80"></textarea><br>
	<input type="submit" value="Send">
	<input type="text" name="_gotcha" style="display:none" />
	<input type="hidden" name="_next" value="/thanks.md" />
</form>
<br>
<script>
    var contactform = document.getElementById('formaction');
    contactform.setAttribute('action', '//formspree.io/' + 'maxraustin' + '@' + 'gmail' + '.' + 'com');
</script>
