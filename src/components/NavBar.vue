<template>
    <section>
        <div class="container" id="home">
            <nav class="navbar navbar-expand-lg">
                <img src="" alt="logo image"
                    style="width: 9em; height: 5em; justify-content: start;">
                    
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span><i class="fas fa-bars" style="color:#ffbe00; font-size:28px;"></i></span>
                </button>

                <div class="collapse navbar-collapse justify-content-end" id="navbarNavAltMarkup">
                    <ul class="navbar-nav" style="column-gap:25px">
                        <li class="nav-item">
                            <a href="#home" class="nav-link text" aria-current="page">Home</a>
                        </li>
                        <li class="nav-item">
                            <a href="#about" class="nav-link text" aria-current="page">About</a>
                        </li>
                        <li class="nav-item">
                            <a href="#car-rent" class="nav-link text" aria-current="page">Car Rent</a>
                        </li>
                        <li class="nav-item">
                            <a href="#services" class="nav-link text" aria-current="page">Services</a>
                        </li>
                        <li class="nav-item">
                            <a href="#blog" class="nav-link text" aria-current="page">Blog</a>
                        </li>
                        <li class="nav-item">
                            <a href="" class="nav-link text" aria-current="page">Contacts</a>
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
    color: black;
    font-size: 1rem;
    font-family: 'Poppins', sans-serif;
    text-decoration: none;
}
a:hover{
    color: #ffdf00 ;
}
.btn{
    width: 10em; 
    height: 3em;
    margin-right: -25px;
    border: none;
    background-color: #ffbe00;
    border-radius: 0px;
}
.btn:hover{
    background-color: white;
    color: #ffbe00;
    border: 1px solid #ffbe00;
}
span{
    font-size: 0.9rem;
}
@media(max-width:991px){
    .btn{
        display: none;
    }
}
</style>