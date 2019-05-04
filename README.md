# jquery.disable-autofill
Disable Chrome's autofill. Handy for CRUD forms, when you don't want username/password inputs to be autofilled by the browser.

Usage:
```
<form>
  <input type="input" name="username" autocomplete="off">
  <input type="password" name="password" autocomplete="off">
</form>

<script src="jquery.disable-autofill.js"></script>
<script>
  $('input[autocomplete="off"]').disableAutofill();
</script>
```
