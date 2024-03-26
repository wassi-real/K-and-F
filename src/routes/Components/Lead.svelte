<script>
    import { fade , fly } from 'svelte/transition'
    let visible = true;
</script>
{#if visible}
<div class="container">
    <h1 transition:fly="{{ y: 200, duration: 2000 }}" >Sustainable Clothing Manufacturers In <br>
    Bangladesh</h1>
    <br>
    <p class="lh-lg" transition:fly="{{ y: 200, duration: 2000 }}">
        From sourcing to manufacturing
        to final delivery,
        Everything is included.
        <br>
        We are one of the most respected textile companies in Bangladesh. We have been manufacturing a large selection of clothing and home textiles since many years. K & F is a brand with a history of quality, excellence and sustainability which has won the trust and confidence of consumers throughout Bangladesh.
    </p>
    <br>
    <br>
    <br>
</div>
{/if}



