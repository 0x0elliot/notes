<h1>Overlooked places where you might find XSS:</h1><br>

<b>1. 404 Errors where they show the name of the page not found:</b>

Example: https://www.openbugbounty.org/reports/1211008/

<b>2. Always try --><script>alert('0x0elliot')</script><!-- As your first payload. Then modify accordingly.</b>

<b>3. If they have banned `<script>` then try <svg onload=alert('0x0elliot')> as your payload.</b><br>

<h1>Bypassing XSS Filters:</h1><br>

<b>1. Remember that you can always use eval(base64_decode()) to anytime you can to Byass any Filters.
