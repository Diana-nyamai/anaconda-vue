<template>
    <nav>
        <div class="menu-item"><a href="#"></a><span>ANACONDA.</span></div>
        <div class="menu-item"><a href="#">Products</a></div>
        <div class="menu-item"><a href="#">Pricing</a></div>
        <div class="menu-item"><a href="#">Solutions</a></div>
        <div class="menu-item"><a href="#">Resources</a></div>
        <div class="menu-item"><a href="#">Blog</a></div>
        <div class="menu-item"><a href="#">Company</a></div>
        <div class="menu-item"><a href="#">Get Started</a></div>
    </nav>
</template>

<script>
    export default {
        name: 'navbar',
        data (){
            return{
                products: [
                    {
                        title: 'Individual edition'
                    },
                    {
                        title: 'Team edition'
                    },
                    {
                        title: 'Enterprise edition'
                    },
                    {
                        title: 'Commercial edition'
                    },
                    {
                        title: 'Anaconda Embedded'
                    },
                    {
                        title: 'professional Services'
                    },
                ]
            }
        }
    }
</script>

<style>
nav{
    width: 100vw;
    display: flex;
    justify-content: center;
    align-items: center;
}
nav .menu-item{
    padding: 10px 20px;
    position: relative;
    text-align: center;
    display: flex;
    transition: 0.4s;
    border-bottom: 2px solid transparent;
}
nav .menu-item:hover{
    border-bottom-color: blue;
}
</style>