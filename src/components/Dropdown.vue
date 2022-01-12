 <template>
    <div class="menu-item" @mouseover="isOpen = !isOpen">
        <a href="#">{{title}}</a>
        <fa icon="caret-down" :style="{ marginLeft: '5px',color: 'grey' }"/>
           
        <transition name="fade" appear>
        <div class="sub-menu" v-if="isOpen">
            <div v-for="(item, i) in items" :key="i" class="menu-item">
                <a :href="item.link">{{item.title}}</a>
            </div>
        </div>
        </transition>
        </div>
</template>

<script>
    export default {
        name: 'dropdown',
        props:['title', 'items'],
        data(){
            return{
                isOpen: false
            }
        }
    }
</script>

<style>
.menu-item{
    display: flex;
    justify-content: center;
    align-items: center;
}
.menu-item .sub-menu{
    position: absolute;
    top: calc(100% - 5px);
    left: 50%;
    transform: translateX(-50%);
    width: max-content;
}
</style>