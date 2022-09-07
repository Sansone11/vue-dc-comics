<template>
  <header>
    <div class="logo-header">
        <img src="../assets/img/dc-logo.png" alt="">
    </div>
    <div>
        <nav class="nav">
            <ul>
                <li class="nav_link" v-for="(link,index) in links" :key="index" :class="[ link.current ? 'active': '' ,nav_link]"> <a :href="link.href">

                {{link.text}}</a></li>
            </ul>
        </nav>
    </div>
  </header>
</template>

<script>

    const links=[
        {
            text:'CHARACTERS',
            href:'#',
        },
        {
            text:'COMICS',
            href:'#',
        },
        {
            text:'MOVIE',
            href:'#',
        },
        {
            text:'TV',
            href:'#',
        },
        {
            text:'GAMES',
            href:'#',
        },
        {
            text:'COLLECTIBLES',
            href:'#',
        },
        {
            text:'VIDEOS',
            href:'#',
        },
        {
            text:'FANS',
            href:'#',
        },
        {
            text:'NEWS',
            href:'#',
        },
        {
            text:'SHOP',
            href:'#',
        },
        
    ]
export default {
   data() {
    return{
        links:links,
    }
   }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    @import './Style/varaibles.scss';
    header {
        max-width: 1250px;
        display: flex;
        justify-content: space-around;
        align-items: center;
        padding: 2rem, 0;
        height: 100px;
    }

    .logo-header{
        max-height: 50px;
        width: 50px;
    }

    .active{
        background-color: $bg-active;
                color: white;
    }

.nav{
    display: inline-block;
    margin-right: auto;
    ul{
        max-width: 200px;
        display: flex;
        align-items: center;
        gap: 1rem;

        .nav_link{
            padding: 0 0.75rem;
            line-height: 1,5rem;

            &.active, &:hover{
                background-color: $bg-active;
                color: white;
            }
        }
    }
}
</style>