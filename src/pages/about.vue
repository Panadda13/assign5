<template>
    <div>
        <Navbar />
        <section class="about">

        <h1 class="heading"> about <span>me</span> </h1>

    <div class="row">

    <div class="info-container">

        <h1>personal info</h1>

        <div class="box-container">

            <div class="box">
                <h3> <span>name : </span> Panadda Sawangphol </h3>
                <h3> <span>age : </span> 20 </h3>
                <h3> <span>email : </span> panadda.sawa@bumail.net </h3>
                <h3> <span>address : </span> Chanthaburi, Thailand 22160 </h3>
            </div>

            <div class="box">
                <h3> <span>university : </span> Bangkok university </h3>
                <h3> <span>faculty : </span> Engineering </h3>
                <h3> <span>department : </span> Multimedia and Entertainment Engineering </h3>
                <h3> <span>language : </span> thai </h3>
            </div>

        </div>


        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: {Navbar}
}
</script>

<style>

</style>