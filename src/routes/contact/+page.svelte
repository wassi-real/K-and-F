<script>
	import { text } from "svelte/internal";
	import Form from "../Components/Form.svelte";
import Hero from "../Components/Hero.svelte";

</script>

<Hero text={"Contact Us"} />
<br>
<br>

<div class="container mt-5">
    <div class="row align-items-center">
        <div class="col-md-6 mb-4 mb-md-0">
            <h3>Want To Work With Us Or Talk?</h3>
            <p>If you have any queries about our garment manufacturing services, get in touch with us via phone or email.</p>
        </div>
        <div class="col-md-6 text-md-right text-center">
            <div class="contact-box p-3 mb-3">
                <h4>Phone: <a href="tel:+8801973082020" class="btn btn-outline-primary btn-custom">+880 1973082020</a></h4>
            </div>
            <div class="contact-box p-3">
                <h4>Email: <a href="mailto:hayat@knfbd.com" class="btn btn-outline-primary btn-custom">hayat@knfbd.com</a></h4>
            </div>
        </div>
    </div>
</div>



<br>
<br>
<br>
<div class="border border-1"></div>
<div class="text-bg-secondary">
<br>
<br>
<div class="container text-center">
    <h3 class="fw-bold">Our Contact Form</h3>
</div>
<br>
<div class="container">
<Form/>
</div>
<br>
<br>
</div>
<div class="mi1">
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
</div>


<style>
    .mi1 {
         background-image: url("https://images.unsplash.com/photo-1476842634003-7dcca8f832de?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTR8fGRhcmt8ZW58MHx8MHx8&auto=format&fit=crop&w=600&q=60");
         background-repeat: no-repeat;
         background-size: cover;
    }


    /* General container padding */
    .container {
        padding: 20px;
    }

    /* Styling for the contact boxes */
    .contact-box {
        border: 2px solid #007bff; /* Border around the box */
        border-radius: 12px; /* Rounded corners */
        background-color: #f9f9f9; /* Light background for contrast */
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow */
    }

    /* Button custom style */
    .btn-custom {
        border-radius: 25px; /* Round button */
        padding: 10px 20px; /* Padding for size */
        transition: all 0.3s ease; /* Smooth transition effect */
        font-size: 1.1rem; /* Slightly larger font */
        text-decoration: none; /* Remove underline */
    }

    /* Button hover effects */
    .btn-custom:hover {
        background-color: #007bff; /* Blue background on hover */
        color: white; /* White text on hover */
        box-shadow: 0px 6px 12px rgba(0, 123, 255, 0.3); /* Glow effect */
        transform: scale(1.05); /* Slight scaling effect */
    }

    /* For larger screens */
    @media (min-width: 768px) {
        .text-md-right {
            text-align: right;
        }
    }

    /* Mobile styles */
    @media (max-width: 767px) {
        .row {
            text-align: center;
        }

        h3 {
            font-size: 1.8rem;
        }

        h4 {
            font-size: 1.3rem;
        }

        p {
            font-size: 1rem;
            margin-bottom: 15px;
        }

        /* Adjusting padding for mobile */
        .contact-box {
            margin-bottom: 15px;
        }
    }
</style>



