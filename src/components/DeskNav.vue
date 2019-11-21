<template>
    <section class="nav">
        <div class="nav-menu">
            <ul class="nav-menu-list">
                <router-link to="/" class="nav-menu-list-item">Home</router-link>
                <router-link to="/contact" class="nav-menu-list-item">Contact</router-link>
                <router-link to="/about" class="nav-menu-list-item">About</router-link>
            </ul>
            
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style scoped>
.nav{
    top:0;
    right:0;
    background: #333;
    display: flex;
    align-items: center;
    width: 100%;
}
.nav-menu{
    color:white;
}
.nav-menu-list{
    line-height: 10vh;
    list-style: none;
    display: inline;
    padding:0;
}
.nav-menu-list-item{
    padding: 10px 20px;
    display: inline;
    cursor: pointer;
    color: white;
    text-decoration: none;
}
.nav-menu-list-item:hover{
    width: 100%;
    background: black;
}
</style>
