---
layout: layouts/base.njk
eleventyNavigation:
  key: Contact Me
  order: 3
---
# Contact Me

Please feel free to contact me on my socials or via the contact form below.

<form name="contact" method="POST" data-netlify="true" class="needs-validation" enctype="multipart/form-data" novalidate>
  <div class="form-row">
    <div class="col-md-4 mb-3">
      <label for="validationCustom01">First name:</label>
      <input type="text" class="form-control" id="validationCustom01" placeholder="First name" value="" required>
      <div class="valid-feedback">
        Looks good!
      </div>
    </div>
    <div class="col-md-4 mb-3">
      <label for="validationCustom02">Surname:</label>
      <input type="text" class="form-control" id="validationCustom02" placeholder="Surname" value="" required>
      <div class="valid-feedback">
        Looks good!
      </div>
    </div>
    <div class="col-md-4 mb-3">
      <label for="validationCustomUsername">Email:</label>
      <div class="input-group">
        <div class="input-group-prepend">
</span>
        </div>
        <input type="email" class="form-control" id="validationCustomUsername" placeholder="Email" aria-describedby="inputGroupPrepend" required>
        <div class="invalid-feedback">
          Please enter an email.
        </div>
      </div>
    </div>
  </div>
  <div class="form-row">
    <div class="col-md-6 mb-3">
      <label for="validationCustom03">Message:</label>
      <textarea class="form-control" id="validationCustom03" placeholder="Message" required></textarea>
      <div class="invalid-feedback">
        Please enter your query.
      </div>
    </div>
  </div>
  <div class="form-group">
    <div class="form-check">
      <input class="form-check-input" type="checkbox" value="" id="invalidCheck" required>
      <label class="form-check-label" for="invalidCheck">
        Terms and conditions
      </label>
      <div class="invalid-feedback">
        You must agree before submitting.
      </div>
    </div>
  </div>
  <button class="btn btn-primary" type="submit">Submit form</button>
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