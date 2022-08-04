<template>
    <section>
        <div class="container navbar-body" id="home">
            <nav class="navbar navbar-expand-lg">                    
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span><i class="fas fa-bars" style="color:#e74c3c; font-size:28px;"></i></span>
                </button>
                <div class="collapse navbar-collapse justify-content-center" id="navbarNavAltMarkup">
                    <ul class="navbar-nav d-flex align-items-center" style="column-gap:25px">
                        <li class="nav-item">
                            <a href="#" class="nav-link text" aria-current="page">About</a>
                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link text" aria-current="page">Services</a>
                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link image-link" aria-current="page"><img src="../assets/Untitled.png" class="image" alt=""></a>
                        </li>
                        <li class="nav-item">
                            <a href="#" class="nav-link text" aria-current="page">Projects</a>
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
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');

a{
    color: white;
    font-size: 1rem;
    font-family: 'Poppins', sans-serif;
    text-decoration: none;
}
a:hover{
    color: #e74c3c;
}
span{
    font-size: 0.9rem;
}
.navbar-body{
    padding: 0.5rem 0;
    padding-left: 1rem;
}
.image{
    width: 5em;
    height: 5em;
}

@media(max-width:991px){
    .image-link{
        display: none;
    }
}
</style>