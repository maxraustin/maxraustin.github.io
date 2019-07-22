# Contact

---

If you would like to get in contact with me, please fill out and submit the form below, and I'll get to it as soon as I can.

NOTE: After clicking send you will be taken to Formspree's site to solve a quick captcha for verification.

<form id="formaction" method="POST">
	<label for="emailID">Email: </label><br>
	<input type="email" name="_replyto" id="emailID"><br>
	<label for="subID">Subject: </label><br>
	<input type="text" id="subID" name="subject"><br>
	<label for="descID">Description: </label><br>
	<textarea name="description" rows="10" cols="50" id="descID"></textarea><br>
	<input type="submit" value="Send">
	<input type="text" name="_gotcha" style="display:none" />
	<input type="hidden" name="_next" value="//maxraustin.github.io/thanks.md" />
</form>
<br>
<script>
    var contactform = document.getElementById('formaction');
    contactform.setAttribute('action', '//formspree.io/' + 'maxraustin' + '@' + 'gmail' + '.' + 'com');
</script>
