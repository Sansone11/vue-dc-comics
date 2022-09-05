<template>
  <header>
    <div class="logo-header">
        <img src="../assets/img/dc-logo.png" alt="">
    </div>
    <div>
        <nav class="nav">
            <ul>
                <li class="nav_link"> <a href="#">CHARACTERS</a></li>
                <li class="nav_link"> <a href="#">COMICS</a></li>
                <li class="nav_link"> <a href="#">MOVIE</a></li>
                <li class="nav_link"> <a href="#">TV</a></li>
                <li class="nav_link"> <a href="#">GAMES</a></li>
                <li class="nav_link"> <a href="#">COLLECTIBLES</a></li>
                <li class="nav_link"> <a href="#">VIDEOS</a></li>
                <li class="nav_link"> <a href="#">FANS</a></li>
                <li class="nav_link"> <a href="#">NEWS</a></li>
                <li class="nav_link"> <a href="#">SHOP</a></li>
            </ul>
        </nav>
    </div>
  </header>
</template>

<script>
export default {
 
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

.nav{
    ul{
        display: flex;
        align-items: center;
        justify-content: end;
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