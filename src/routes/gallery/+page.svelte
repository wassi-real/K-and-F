<script>
    import { onMount } from 'svelte';
    let loading = true;
    let iframeLoaded = false;
  
    // Function to hide the loading screen and show the iframe
    function hideLoadingScreen() {
      loading = false;
      iframeLoaded = true; // Ensure iframe is visible
    }
  
    // Function to redirect to the home screen
    function closeGallery() {
      window.location.href = '/';
    }
  
    // Ensure the iframe is hidden initially and show it once loaded
    onMount(() => {
      const iframe = document.getElementById('gallery-iframe');
      iframe.onload = hideLoadingScreen;
    });
  </script>
  

  
  {#if loading}
    <div class="loading-screen">
      <div class="loading-animation">
        <!-- <h3 class="fw-bolder">Accessing Server, Please Wait...</h3> -->
        <div class="spinner"></div>
      </div>
    </div>
  {/if}
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <div class="container text-center">
    <h3 class="fw-bolder">Gallery is now Loading...</h3>
  </div>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <br>
  <!-- svelte-ignore a11y-missing-attribute -->
  <iframe id="gallery-iframe" class="responsive-iframe {iframeLoaded ? 'iframe-visible' : ''}" src="https://knf.picflow.com/go75r71oco"></iframe>
  
  <!-- <button id="close-btn" class="close-btn  ty" on:click={closeGallery}>
    &times;
  </button> -->


<style>
    .loading-screen {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(255, 255, 255, 0.9); /* Light overlay with slight transparency */
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 999999;
    }
  
    .loading-animation {
      text-align: center;
    }
  
    .spinner {
      margin-top: 20px;
      border: 8px solid #f3f3f3;
      border-top: 8px solid #007bff;
      border-radius: 50%;
      width: 50px;
      height: 50px;
      animation: spin 1s linear infinite;
    }
  
    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
  
    .responsive-iframe {
      position: fixed;
      top: 0;
      left: 0;
      bottom: 0;
      right: 0;
      width: 100%;
      height: 100%;
      border: none;
      display: none; /* Hide iframe initially */
    }
  
    .iframe-visible {
      display: block; /* Show iframe after loading */
    }
  
    /* .close-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 50%;
      width: 50px;
      height: 50px;
      font-size: 24px;
      display: flex;
      justify-content: center;
      align-items: center;
      cursor: pointer;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
      transition: background-color 0.3s;
    } */
  
    /* .close-btn:hover {
      background-color: #0056b3;
    }
  
    .close-btn:focus {
      outline: none;
    } */
</style>