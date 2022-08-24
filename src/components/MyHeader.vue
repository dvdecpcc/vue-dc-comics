<template>
  <header>
    <div>
        <img src="../assets/img/dc-logo.png" alt="dc logo">
    </div>
    <div>
        <ul>
            <li v-for="(liink, index) in links" :key=index>
                <a :href="liink.url">{{link.text}}</a>
            </li>
        </ul>
    </div>
  </header>
</template>

<script>
export default {
    name: 'MyHeader',
    data(){
        return{
            links:[
                {
                    text: 'CHARACTERS',
                    url: '#',
                    active: false
                },
                {
                    text: 'COMICS',
                    url: '#',
                    active: false
                },
                {
                    text: 'MOVIES',
                    url: '#',
                    active: false
                },
                {
                    text: 'TV',
                    url: '#',
                    active: false
                },
                {
                    text: 'GAMES',
                    url: '#',
                    active: false
                },
                {
                    text: 'COLLECTIBLES',
                    url: '#',
                    active: false
                },
                {
                    text: 'VIDEOS',
                    url: '#',
                    active: false
                },
                {
                    text: 'FANS',
                    url: '#',
                    active: false
                },
                {
                    text: 'NEWS',
                    url: '#',
                    active: false
                },
                {
                    text: 'SHOP',
                    url: '#',
                    active: false
                }
            ]
        }
    }
}
</script>

<style lang="scss">
    header{
        display: flex;
        justify-content: space space-between;
        align-items: center;
        height: 100px;
        width: 80%;
    }
    li{
        display: inline-block;
        text-decoration: none;
        padding: 0px, 15px;
    }
    a{
        font-weight: bolder;
        color: rgb(84, 79, 85);
        text-decoration: none;
        &:hover{
            cursor: pointer;
            color: rgb(1, 130, 249);
        }
    }

</style>