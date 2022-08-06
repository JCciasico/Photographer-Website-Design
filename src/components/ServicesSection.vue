<template>
  <section>
    <div class="container">
        <div class="row d-flex justify-content-center" id="services">
            <div class="col-9">
                <div class="row">
                    <div class="col-12 image" data-aos="zoom-in">
                    </div>
                    <div class="col-lg-6 col-md-12 col-sm-12 image-1" data-aos="fade-right">
                        
                    </div>
                    <div class="col-lg-6 col-md-12 col-sm-12 services-cont text-center" data-aos="fade-left">
                        <div>
                            <span>Services</span>
                            <div class="services-des">
                                <p>I delivered the highest quality services
                                in the following fields: Photography, Filmmaking,
                                Cinematography.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Philosopher:wght@400;700&display=swap');


.image{
    background: url("../assets/brent-ninaber-6qesnUQceJA-unsplash.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    height: 250px;
}
.image-1{
    padding: 0;
    background: url("../assets/dariusz-sankowski-3OiYMgDKJ6k-unsplash.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}
span{
    font-family: 'Philosopher', sans-serif;
    font-weight: 700;
    font-size: 2.5rem;
    padding: 1.5rem 0;
    border-bottom: 1px solid #ced6e0;
}
.services-cont{
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 9rem 0;
}
.services-des{
    font-family: 'Philosopher', sans-serif;
    color: #747d8c;
    margin-top: 30px;
}
@media(max-width: 991px){
    .services-cont{
        padding: 6rem 0;
    }
}
@media(max-width:500px){
    span{
        font-size: 1.5rem;
        padding: 1rem 0;
    }
    .services-cont{
        padding: 0.7rem 0;
    }
}
</style>