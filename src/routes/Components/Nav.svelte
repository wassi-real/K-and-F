<script>
  // Import Bootstrap Offcanvas API
  import { onMount } from "svelte";

  let offcanvasElement;

  onMount(() => {
    // Initialize Bootstrap Offcanvas using JavaScript API
    const offcanvas = new bootstrap.Offcanvas(offcanvasElement);
    
    // Find all nav links and add an event listener
    const navLinks = document.querySelectorAll(".nav-link");

    navLinks.forEach((link) => {
      link.addEventListener("click", () => {
        // Hide the offcanvas when a link is clicked
        offcanvas.hide();
      });
    });
  });
</script>

<nav class="navbar  fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="/">
      <img
        src="https://ik.imagekit.io/atg/k-removebg-preview_RA99YBIST.png?ik-sdk-version=javascript-1.4.3&updatedAt=1664530556963"
        alt=""
        srcset=""
        height="60"
      />
    </a>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="offcanvas"
      data-bs-target="#offcanvasNavbar"
      aria-controls="offcanvasNavbar"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div
      class="offcanvas offcanvas-end"
      tabindex="-1"
      id="offcanvasNavbar"
      aria-labelledby="offcanvasNavbarLabel"
      bind:this={offcanvasElement}
    >
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasNavbarLabel">
          <a class="navbar-brand" href="/">
            <img
              src="https://ik.imagekit.io/atg/k-removebg-preview_RA99YBIST.png?ik-sdk-version=javascript-1.4.3&updatedAt=1664530556963"
              alt=""
              srcset=""
              height="60"
            />
          </a>
        </h5>
        <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
      </div>
      <div class="offcanvas-body">
        <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
          <li class="nav-item">
            <a class="nav-link fw-bold" href="/">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link fw-bold" aria-current="page" href="/about">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link fw-bold" href="/products">Our Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link fw-bold" href="/gallery">View Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link fw-bold" href="/contact">Contact Us</a>
          </li>
        </ul>
        <br />
        <br />
        <p class="text-muted mt-5 text-center">
          <i class="bi bi-envelope-fill"></i>
          <a href="mailto:hayat@knfbd.com">hayat@knfbd.com</a>
        </p>
      </div>
    </div>
  </div>
</nav>





<style>
    .navbar-toggler {
            /* border-color: rgb(0, 187, 250); */
            border-radius: 4px;
            border: none;
            background-color: white;
            /* color: white; */
            
    }
    .navbar-toggler-icon {
      border-color: rgb(0, 187, 250);
    }
    .navbar {
  background: none;
}
</style>