<br>
<br>
<br>
<div class="container">
    <div class="row">
        <!-- First Column: Services -->
        <div class="col-lg-6 col-md-12 order-2 order-lg-1"> <!-- Order changes for mobile -->
            <img 
            src="https://ik.imagekit.io/softodesign/23.jpg?updatedAt=1725811558565" 
            class="shadow-lg img-fluid w-100 img-services"
            alt="">
            <br>
            <br>
            <br>
            <h3>Services</h3>
            <p class="tex-muted">
                Our styling and manufacturing abilities have been built from years of experience in the fashion industry. We are able to create clothing on a variety of levels and within every budget. We make sure that each piece we produce is crafted with care, attention to detail and utilises only the finest fabrics. The result is well-made, modern designs that are an absolute pleasure to wear.                
            </p>
            <a href="/about" class="btn btn-outline-primary">
                Learn More
            </a>
        </div>

        <!-- Second Column: Product -->
        <div class="col-lg-6 col-md-12 order-1 order-lg-2 mt-5"> <!-- Order changes for mobile -->
            <h3>Product.</h3>
            <p class="tex-muted">
                K&F is a well-established and trusted clothing manufacturer in Bangladesh. We specialize in producing quality garments, stylish dresses and tops. All our products are made from the finest fabrics soakes "Creating Quality Fabrics"
            </p>
            <a href="/about" class="btn btn-outline-primary">
                Learn More
            </a>
            <br>
            <br>
            <img 
            src="https://ik.imagekit.io/softodesign/25.jpg?updatedAt=1725811632535" 
            class="shadow-lg img-fluid w-100 img-product"
            alt="">
        </div>
    </div>
</div>

<br>
<br>



<style>
    img {
        border-radius: 13px;
        /* height: 100%; */
        /* width: 50%; */
    }


    /* Custom height for images on mobile */
    .img-services,
    .img-product {
    max-height: 300px; /* Ensure images have better height on small screens */
    object-fit: cover; /* Ensures the image scales correctly without being distorted */
    }

    /* Custom layout for smaller screens */
    @media (max-width: 768px) {
    .img-services,
    .img-product {
        margin-top: 20px;
        max-height: 400px; /* Slightly larger image on mobile */
        width: 100%; /* Ensures images take full width of mobile */
    }
    }

</style>