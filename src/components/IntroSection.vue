<template>
  <section>
    <div class="container intro-body" data-aos="zoom-in" data-aos-duration="2000">
        <h1>
            The truth behind
        </h1>
        <h6>
            A creative portfolio of Photographer
        </h6>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Philosopher:wght@400;700&display=swap');

.intro-body{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 12rem 0;
    color: white;
}
h1{
    font-family: 'Philosopher', sans-serif;
    font-size: 5rem;
    font-weight: 700;
}
h6{
    font-family: 'Philosopher', sans-serif;
    font-size: 1.5rem;
    margin-top: 10px;
    margin-bottom: 100px;
}
@media(max-width:800px){
    h1{
        font-size: 4rem;
    }
    h6{
        font-size: 1.2rem;
    }
}
@media(max-width:500px){
    h1{
        font-size: 3rem;
    }
    h6{
        font-size: 1rem;
    }
}
@media(max-width:400px){
    h1{
        font-size: 2.3rem;
    }
    h6{
        font-size: 1rem;
    }
    .intro-body{
        padding: 9rem 0;
    }
}

</style>