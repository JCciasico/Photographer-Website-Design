<template>
  <section>
    <div class="container welcome-body">
        <div class="row d-flex justify-content-center">
            <div class="col-8">
                <span>Welcome</span>
                <p>I am filmmaker, a photographer and a philisopher.
                    By capturing the reality I seek the truth, hidden
                    in every piece of existence.
                </p>
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
p{
    margin-top: 50px;
    color: #747d8c;
    font-family: 'Philosopher', sans-serif;
}
@media(max-width:500px){
    span{
        font-size: 1.5rem;
        padding: 1rem 0;
    }
}
</style>