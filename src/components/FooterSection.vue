<template>
  <section>
    <div class="container footer-body">
        <div class="row">
            <div class="col-lg-12 col-md-12 text-center contact-body">
                <h1><span>Let us work together</span></h1>
                <button>Contact Me</button>
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


span{
    font-family: 'Philosopher', sans-serif;
    font-weight: 700;
    font-size: 2.5rem;
    padding: 1rem 0;
    border-bottom: 1px solid white;
    color: white;
}
.contact-body{
    padding-top: 8rem;
    padding-bottom: 7rem;
}
button{
    margin-top: 70px;
    padding: 0.7rem;
    width: 175px;
    font-family: 'Philosopher', sans-serif;
    background: none;
    color: white;
    border: 2px solid white;
}
button:hover{
    transform: scale(1.035);
}
@media(max-width:500px){
    span{
        font-family: 'Philosopher', sans-serif;
        font-weight: 700;
        font-size: 1.5rem;
        padding: 1rem 0;
        border-bottom: 1px solid #747d8c;
    }
    button{
        margin-top: 60px;
        padding: 0.5rem;
        width: 125px;
        font-family: 'Philosopher', sans-serif;
        background: none;
    }
}
</style>