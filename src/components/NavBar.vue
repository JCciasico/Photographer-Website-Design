<template>
    <section>
        <div class="container navbar-body" id="home">
            <nav class="navbar navbar-expand-lg">                    
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span><i class="fas fa-bars" style="color:#00fefc; font-size:28px;"></i></span>
                </button>
                <div class="collapse navbar-collapse justify-content-center" id="navbarNavAltMarkup">
                    <ul class="navbar-nav" style="column-gap:25px">
                        <li class="nav-item">
                            <a href="#about" class="nav-link text" aria-current="page">About</a>
                        </li>
                        <li class="nav-item">
                            <a href="#services" class="nav-link text" aria-current="page">Services</a>
                        </li>
                        <li class="nav-item">
                            <img src="../assets/logo-1.png"  class="nav-link image-link image" alt="">
                        </li>
                        <li class="nav-item">
                            <a href="#project" class="nav-link text" aria-current="page">Projects</a>
                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link text" aria-current="page">Contact</a>
                        </li>
                    </ul>
                </div>
            </nav>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Philosopher:wght@400;700&display=swap');

a{
    color: white;
    font-size: 1rem;
    font-family: 'Philosopher', sans-serif;
    text-decoration: none;
}
a:hover{
    color: #00fefc;
}
span{
    font-size: 0.9rem;
}
.navbar-body{
    padding: 1rem 0;
    padding-left: 2rem;
}
.image{
    width: 4em;
    height: 3em;
}

@media(max-width:991px){
    .image-link{
        display: none;
    }
}
</style>