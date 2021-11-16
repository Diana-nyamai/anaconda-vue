<template>
    <div class="menu-item">
        <a href="#">{{title}}</a>
        <fa icon="caret-down" :style="{ marginLeft: '5px',color: 'grey' }"/>
        </div>
</template>

<script>
    export default {
        name: 'dropdown',
        props:['title', 'items'],
    }
</script>

<style>
.menu-item{
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>