<template>
  <section>
    <div class="container">
        <div class="row text-center d-flex justify-content-center">
            <div class="col-8 feature-body">
                <p id="feature">Featured project</p>
                <span>Restless dreams</span>
                <p id="title">Dark alley and silent hills</p>
                <button>Follow me</button>
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

.feature-body{
    padding: 8rem 0;
}
span{
    font-family: 'Philosopher', sans-serif;
    font-weight: 700;
    font-size: 3rem;
    padding: 1.5rem 0;
    color: #dfe4ea;
    border-bottom: 1px solid #a4b0be;
}
#title{
    padding: 3rem;
    color: #dfe4ea;
    font-family: 'Philosopher', sans-serif;
}
#feature{
    color: #dfe4ea;
    font-family: 'Philosopher', sans-serif;
}
button{
    padding: 0.8rem;
    width: 200px;
    background:none;
    border: 3px solid #dfe4ea;
    color: #dfe4ea;
    font-family: 'Philosopher', sans-serif;
}
button:hover{
    background:none;
    color: #00fefc;
    border: 3px solid #00fefc;
}
@media(max-width:500px){
    span{
        font-size: 2rem;
        padding: 1rem 0;
    }
    button{
        padding: 0.5rem;
        width: 120px;
        border: 2px solid #dfe4ea;
    }
    button:hover{
        background:none;
        color: #00fefc;
        border: 2px solid #00fefc;
    }
}
</style>