
<form action="https://formpost.app/hayat@knfbd.com" method="POST" id="contactForm">
  <input type="hidden" name="fp_redirect" value="http://localhost:5173/thanks">
  
  <div class="mb-4">
    <label for="fullName" class="form-label">Your Full Name</label>
    <input type="text" name="name" class="form-control" id="fullName" placeholder="John" required>
    <div class="invalid-feedback">Please enter your full name.</div>
  </div>

  <div class="mb-4">
    <label for="email" class="form-label">Email Address</label>
    <input type="email" name="email" class="form-control" id="email" placeholder="name@example.com" required>
    <div class="invalid-feedback">Please enter a valid email address.</div>
  </div>

  <div class="mb-4">
    <label for="message" class="form-label">Your Message</label>
    <textarea class="form-control" name="message" id="message" rows="4" required></textarea>
    <div class="invalid-feedback">Please enter your message.</div>
  </div>

  <div class="mb-4">
    <button type="submit" class="btn btn-primary btn-lg">Send Message</button>
  </div>
</form>


<style>
  /* General form styling */
  form {
      max-width: 600px; /* Set maximum width for larger screens */
      margin: auto; /* Center the form horizontally */
      padding: 20px; /* Add padding around the form */
      background-color: #f9f9f9; /* Light background color */
      border-radius: 12px; /* Rounded corners for the form */
      box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow effect */
  }

  /* Styling for form labels */
  .form-label {
      font-weight: bold;
      margin-bottom: 10px;
      display: block;
  }

  /* Styling for form inputs */
  .form-control {
      border-radius: 8px; /* Rounded corners for inputs */
      border: 1px solid #ddd; /* Light border color */
      padding: 10px; /* Add padding inside inputs */
  }

  /* Styling for the submit button */
  .btn-primary {
      background-color: #007bff; /* Primary blue color */
      border: none; /* Remove default border */
      border-radius: 25px; /* Round button corners */
      padding: 12px 24px; /* Add padding to button */
      font-size: 1.1rem; /* Larger font size for readability */
      transition: all 0.3s ease; /* Smooth transition for hover effect */
  }

  .btn-primary:hover {
      background-color: #0056b3; /* Darker blue color on hover */
      box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.2); /* Shadow effect on hover */
      transform: scale(1.05); /* Slightly enlarge button on hover */
  }

  /* Custom error message styling */
  .invalid-feedback {
      display: none; /* Hide error messages by default */
      color: #dc3545; /* Red color for error messages */
      font-size: 0.875rem; /* Smaller font size */
  }

  
</style>
