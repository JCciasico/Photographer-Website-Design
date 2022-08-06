<template>
  <section>
    <div class="container welcome-body">
        <div class="row d-flex justify-content-center">
            <div class="col-8">
                <span>Art in numbers</span>
                <div class="row number-body">
                    <div class="col" data-aos="fade-down" data-aos-duration="500">
                        <h1>879</h1>
                        <p>photographs</p>
                    </div>
                    <div class="col" data-aos="fade-down" data-aos-duration="1000">
                        <h1>52</h1>
                        <p>movie projects</p>
                    </div>
                    <div class="col" data-aos="fade-down" data-aos-duration="1500">
                        <h1>104</h1>
                        <p>awards</p>
                    </div>
                    <div class="col" data-aos="fade-down" data-aos-duration="2000">
                        <h1>12</h1>
                        <p>lenses</p>
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

.welcome-body{
    padding: 3rem 0;
    text-align: center;
}
span{
    font-family: 'Philosopher', sans-serif;
    font-weight: 700;
    font-size: 2.5rem;
    padding: 1.5rem 0;
    border-bottom: 1px solid #ced6e0;
}
.number-body{
    margin-top: 50px;
}
h1{
    font-family: 'Philosopher', sans-serif;
    font-weight: 700;
    color: #57606f;
}
p{
    font-family: 'Philosopher', sans-serif;
    color: #57606f;
}
@media(max-width:500px){
    span{
        font-size: 1.5rem;
        padding: 1rem 0;
    }
}
</style>