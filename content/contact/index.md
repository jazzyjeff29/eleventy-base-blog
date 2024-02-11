---
layout: layouts/base.njk
eleventyNavigation:
  key: Contact Me
  order: 3
---
# Contact Me

Please feel free to contact me on my socials or via the contact form below (coming soon).

 <form class="needs-validation" novalidate>
  <div class="form-group">
    <label for="fName">First Name:</label><br>
    <input type="text" class="form-control" id="fName" placeholder="First Name" required/><br>
      <div class="valid-feedback">
        Looks good!
      </div>
    <label for="sName">Surname:</label><br>
    <input type="text" class="form-control" id="sName" placeholder="Last Name" required/><br>
      <div class="valid-feedback">
        Looks good!
      </div>
    <label for="email">Email:</label><br>
    <input type="text" class="form-control" id="email" placeholder="name@example.com" required/><br>
      <div class="invalid-feedback">
        Please provide a valid email.
      </div>
    <label for="message">Message:</label><br>
    <textarea id="message" class="form-control" name="message " row="4" cols="50" placeholder="Message" required></textarea><br>
      <div class="invalid-feedback">
        Please provide a valid message.
      </div>
    <div class="form-group">
      <div class="form-check">
      <input class="form-check-input" type="checkbox" id="tandc" name="tandc" value="tnc" required>
      <label class="form-check-label" for="tandc"> Terms and conditions</label><br>
      <div class="invalid-feedback">
        You must agree before submitting.
      </div>
    </div>
  </div>
      <input type="button" value="Submit"/>
  </form>

  <footer>
    <p><em>&copy; 2024 JS Ltd</em></p>
  </footer>

  <script>
// Example starter JavaScript for disabling form submissions if there are invalid fields
(function() {
  'use strict';
  window.addEventListener('load', function() {
    // Fetch all the forms we want to apply custom Bootstrap validation styles to
    var forms = document.getElementsByClassName('needs-validation');
    // Loop over them and prevent submission
    var validation = Array.prototype.filter.call(forms, function(form) {
      form.addEventListener('submit', function(event) {
        if (form.checkValidity() === false) {
          event.preventDefault();
          event.stopPropagation();
        }
        form.classList.add('was-validated');
      }, false);
    });
  }, false);
})();
</script>