# ticketlourenndigital
Ticket Lourenn Digital
<form oninput="total.value = (nights.valueAsNumber * 99) + 
 ((guests.valueAsNumber - 1) * 10)">

  <label>Full name:</label>
  <input type="text" id="full_name" name="full_name" placeholder="Jane Doe" required>

  <label>Email address:</label>
  <input type="email" id="email_addr" name="email_addr" required>

  <label>Repeat email address:</label>
  <input type="email" id="email_addr_repeat" name="email_addr_repeat" required 
   oninput="check(this)">

  <label>Arrival date:</label>
  <input type="date" id="arrival_dt" name="arrival_dt" required>
  
  <label>Number of nights (rooms are $99.00 per night):</label>
  <input type="number" id="nights" name="nights" value="1" min="1" max="30" required>

  <label>Number of guests (each additional guest adds $10.00 per night):</label>
  <input type="number" id="guests" name="guests" value="1" min="1" max="4" required>

  <label>Estimated total:</label>
  $<output id="total" name="total">99</output>.00
  <br><br>

  <label>Promo code:</label>
  <input type="text" id="promo" name="promo" pattern="[A-Za-z0-9]{6}" 
   title="Promo codes consist of 6 alphanumeric characters.">

  <input type="submit" value="Request Reservation" /> 
</form>

<script>
function check(input) {
  if (input.value != document.getElementById('email_addr').value) {
    input.setCustomValidity('The two email addresses must match.');
  } else {
    // input is valid -- reset the error message
    input.setCustomValidity('');
  }
}
</script>
