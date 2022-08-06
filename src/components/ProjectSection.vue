<template>
  <section>
    <div class="container">
        <div class="row d-flex justify-content-center">
            <div class="col-lg-9 col-md-9 col-sm-12">
                <div class="row">
                    <div class="col-lg-6 col-md-12 img-1" data-aos="fade-right">
                        <h2>Tell me you dont want</h2>
                    </div>
                    <div class="col-lg-6 col-md-12">
                        <div class="row">
                            <div class="col-12 img-2" data-aos="fade-left">
                                <h2>Nights & Colours</h2>
                            </div>
                            <div class="col-12 img-3" data-aos="fade-left">
                                <h2>Ontario Lake</h2>
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

.img-1{
    background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)),  url("../assets/miss-zhang-jz0xIgcwyL0-unsplash.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    padding: 15rem 3rem;
    display: flex;
    align-items: center;
    justify-content: center;
}
.img-2{
    background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)),  url("../assets/juan-felipe-Kk8mEQAoIpI-unsplash.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    padding: 7.5rem 3rem;
    display: flex;
    align-items: center;
    justify-content: center;
}
.img-3{
    background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)),  url("../assets/claudia-chiavazza-N9vsB6OEeKM-unsplash.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    padding: 7.5rem 3rem;
    display: flex;
    align-items: center;
    justify-content: center;
}
h2{
    font-family: 'Philosopher', sans-serif;
    color: white;
    font-weight: 700;

}
h2:hover{
    transform: scale(1.035);
    cursor: pointer;
    color: #00fefc;
}
@media(max-width:991px){
    .img-1{
    background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)),  url("../assets/miss-zhang-jz0xIgcwyL0-unsplash.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    padding: 6rem 3rem;
    display: flex;
    align-items: center;
    justify-content: center;
}
.img-2{
    background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)),  url("../assets/juan-felipe-Kk8mEQAoIpI-unsplash.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    padding: 6rem 3rem;
    display: flex;
    align-items: center;
    justify-content: center;
}
.img-3{
    background: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)),  url("../assets/claudia-chiavazza-N9vsB6OEeKM-unsplash.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    padding: 6rem 3rem;
    display: flex;
    align-items: center;
    justify-content: center;
}
}

</style>