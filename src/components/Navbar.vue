<template>
    <nav>
        <div class="menu-item"><a href="#"></a><span>ANACONDA.</span></div>
        <dropdown title="Products" :items="products"/>
        <div class="menu-item"><a href="#">Pricing</a></div>
        <dropdown title="Solutions" :items="products"/>
        <dropdown title="Resources" :items="products"/>
        <div class="menu-item"><a href="#">Blog</a></div>
        <dropdown title="Company" :items="products"/>
        <div class="menu-item"><a href="#">Get Started</a></div>
    </nav>
</template>

<script>
import Dropdown from './Dropdown.vue'
    export default {
        name: 'navbar',
        components:{
            Dropdown

        },
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
    border-bottom-color: #43b049;
}
</style>