<template>
  <section>
    <div class="container soc-body">
        <div class="box-1">
            <i class="fa-brands fa-facebook-f"></i>
        </div>
        <div class="box-2">
            <i class="fa-brands fa-instagram"></i>
        </div>
        <div class="box">
            <i class="fa-brands fa-twitter"></i>
        </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>

.soc-body{
    display: flex;
    justify-content: center;
    align-items: center;
    column-gap: 25px;
    padding: 0.5rem 0;
}
.box{
    background-color: #2f3542;
    padding: 0.75rem 1rem;
    border-radius: 50%;
    color: white;
}
.box:hover{
    color: #1e90ff;
    cursor: pointer;
}
.box-1{
    background-color: #2f3542;
    padding: 0.75rem 1.2rem;
    border-radius: 50%;
    color: white;
}
.box-1:hover{
    color: #1e90ff;
    cursor: pointer;
}
.box-2{
    background-color: #2f3542;
    padding: 0.75rem 1.1rem;
    border-radius: 50%;
    color: white;
}
.box-2:hover{
    color: #ff4757;
    cursor: pointer;
}
</style>