<script>
	import Client from "./Components/Client.svelte";
	import Cont from "./Components/Cont.svelte";
	import End from "./Components/End.svelte";
	import Feat from "./Components/Feat.svelte";
import Lead from "./Components/Lead.svelte";
	import Lead2 from "./Components/Lead2.svelte";
	import Lol from "./Components/Lol.svelte";
	import Slide from "./Components/Slide.svelte";


</script>
<div class="main shadow">
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <div class="container mt-5">
        <h1 class="text-white fw-bold"><b>K&F <br> DRESS BD  </b></h1>
        <br>
        <p class="text-white fs-4">We Turn Your Clothing Idea Into Reality</p>
        <a href="/contact"><button class="btn btn-primary btn-lg">Talk To Us</button></a>
        <br>
        <br>
        <br>
    </div>
    <br>
    <br>
    <br>
</div>
<!-- <div>
            <img 
        src="https://images.unsplash.com/photo-1602810318383-e386cc2a3ccf?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80" 
        alt="n"
        class="shadow-lg img-fluid"
        width="100%"
        >
      
</div> -->
<br>
<br>
<br>
<Lead/>
<Lead2/>
<br>
<br>
<br>
<Feat/>
<Slide/>
<br>
<br>
<br>
<br>
<br>
<Cont/>
<br>
<br>
<br>
<Client/>
<Lol/>
<End/>

<style>
    h1 {
        font-size: 60px;
    }
    

   

    .main {/*as per your preferences*/
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        animation-name: example;
        animation-duration: 25s;
        animation-iteration-count: infinite;
        animation-delay: 30;

    }

    @keyframes example{
            0%{
                background-image: url("https://images.unsplash.com/photo-1613076321656-23dcdd3aea92?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MjF8fHRleHRpbGV8ZW58MHwwfDB8fA%3D%3D&auto=format&fit=crop&w=600&q=60");
            }
            30%{
                background-image: url("https://images.unsplash.com/photo-1459792323369-14e51bb68de0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1yZWxhdGVkfDV8fHxlbnwwfHx8fA%3D%3D&auto=format&fit=crop&w=600&q=60");
            }
            50%{
                background-image: url("https://images.unsplash.com/photo-1560796952-f1c9b838544c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1yZWxhdGVkfDN8fHxlbnwwfHx8fA%3D%3D&auto=format&fit=crop&w=600&q=60");
            }
            70%{
                background-image: url("https://images.unsplash.com/photo-1593250816874-8edf4f732edb?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NXx8dGV4dGlsZXxlbnwwfDB8MHx8&auto=format&fit=crop&w=600&q=60");
            }
            100%{
                background-image: url("https://images.unsplash.com/photo-1524292332709-b33366a7f165?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8dGV4dGlsZXxlbnwwfDB8MHx8&auto=format&fit=crop&w=600&q=60");
            }
        }


        /* Setting the stroke to green using rgb values (0, 128, 0) */
          
</style>