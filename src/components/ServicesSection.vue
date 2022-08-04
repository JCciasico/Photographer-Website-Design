<template>
  <section>
    <div class="container">
        <div class="row d-flex justify-content-center">
            <div class="col-9">
                <div class="row">
                    <div class="col-12 image">
                    </div>
                    <div class="col-6 image-1">
                        <img src="../assets/dariusz-sankowski-3OiYMgDKJ6k-unsplash.jpg" class="img-fluid" alt="">
                    </div>
                    <div class="col-6 services-cont text-center">
                        <div>
                            <span>Services</span>
                            <div class="services-des">
                                <p>I delivered the highest quality services <br>
                                in the following fields:</p>
                                <p>Photography</p>
                                <p>Filmmaking</p>
                                <p>Cinematography</p>
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
}
.services-des{
    font-family: 'Philosopher', sans-serif;
    color: #747d8c;
    margin-top: 30px;
}
</style>