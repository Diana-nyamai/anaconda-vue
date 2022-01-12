<template>
    <nav>
        <div class="menu-item"><a href="#"><img :src="logo" width="40" height="40" alt="logo"></a><span>ANACONDA.</span></div>
        <dropdown title="Products" :items="products"/>
        <div class="menu-item green"><a href="#">Pricing</a></div>
        <dropdown title="Solutions" :items="solutions"/>
        <dropdown title="Resources" :items="products"/>
        <div class="menu-item green"><a href="#">Blog</a></div>
        <dropdown title="Company" :items="products"/>
        <div class="menu-item"><a href="#" class="g-started">Get Started</a></div>
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
                logo: require('../assets/favicon.png'),   
                products: [
                    {
                        title: 'Individual edition',
                        link: 'hhhhhh'
                    },
                    {
                        title: 'Team edition',
                        link: 'hhhhhh'
                    },
                    {
                        title: 'Enterprise edition',
                        link: 'hhhhhh'
                    },
                    {
                        title: 'Commercial edition',
                        link: 'hhhhhh'
                    },
                    {
                        title: 'Anaconda Embedded',
                        link: 'hhhhhh'
                    },
                    {
                        title: 'professional Services',
                        link: 'hhhhhh'
                    },
                ],
                solutions: [
                    {
                        title: 'diana',
                        link: 'hhhh'
                    },
                    {
                        title: 'diana',
                        link: 'hhhh'
                    },
                    {
                        title: 'diana',
                        link: 'hhhh'
                    },
                    {
                        title: 'diana',
                        link: 'hhhh'
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
nav .menu-item .g-started{
    padding: 0.4em 1.5em;
    border: 2px solid #0b2227;
    background: #0b2227;
    border-radius: 25em;
    box-shadow: 0 2px 5px rgb(0 0 0 / 30%);
    transition: all .2s;
    color: #fff;
}
nav .menu-item .g-started:hover{
    background: #005a87;
    border: 2px solid #005a87;
    box-shadow: 0 4px 10px rgb(0 0 0 / 50%);
}

</style>