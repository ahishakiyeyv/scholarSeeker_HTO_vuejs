<template>
    <header>
        <div class="logo">
            <img src="../assets/images/logo.png" alt="unavalaible">
        </div>
        <nav>
            <ul>
                <li>
                    <router-link class="link">Home</router-link>
                </li>
                <li>
                    <router-link class="link">About Us</router-link>
                </li>
                <li>
                    <router-link class="link">FAQs</router-link>
                </li>
            </ul>
        </nav>
        <div class="btn">
            <router-link class="btn-link">Help Center</router-link>
        </div>
    </header>
</template>
<style scoped>
header{
    display:flex;
    align-items:center;
    justify-content:space-between;
    position:fixed;
    width:100%;
    padding:.5rem 5rem .5rem 8rem;
    z-index:1000;
    backdrop-filter: blur(4px);
    box-shadow: 0px 1px 5px 0px rgba(0,0,0,0.75);
}
nav ul{
    display: flex;
    justify-content: space-around;
}
nav ul li{
    padding:0 1.2rem;
    list-style: none;
}
nav ul li .link{
    text-decoration:none;
    color:var(--text-color);
    font-weight:600;
}
.logo img{
    height:70px;
    width:70px;
}
.btn .btn-link{
    background-color:var(--title-color);
    color:white;
    padding:.5rem 1rem;
    border-radius:5px;
    text-decoration:none;
    font-weight:600;
    transition: background-color 0.3s ease;
}
</style>