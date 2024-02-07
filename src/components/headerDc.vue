<script>
    export default {
        name: "headerDc"
    }
</script>






<template>
    <div id="headerBg">
        <div class="d-flex align-items-center justify-content-between w-75 m-auto">
            <img src="../assets/img/dc-logo.png" alt="Logo">
            <div>
                <ul class="d-flex gap-4">
                    <li>
                        <a href="#" class="text-uppercase active">characters</a>
                    </li>
                    <li>
                        <a href="#" class="text-uppercase">comics</a>
                    </li>
                    <li>
                        <a href="#" class="text-uppercase">movies</a>
                    </li>
                    <li>
                        <a href="#" class="text-uppercase">tv</a>
                    </li>
                    <li>
                        <a href="#" class="text-uppercase">games</a>
                    </li>
                    <li>
                        <a href="#" class="text-uppercase">collectibles</a>
                    </li>
                    <li>
                        <a href="#" class="text-uppercase">videos</a>
                    </li>
                    <li>
                        <a href="#" class="text-uppercase">fans</a>
                    </li>
                    <li>
                        <a href="#" class="text-uppercase">news</a>
                    </li>
                    <li>
                        <a href="#" class="text-uppercase">shop</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
    
    

  


</template>








<style lang="scss" scoped>
    #headerBg{
        padding-block: 2rem;
        background-color: white;
        div{
            img{
                width: 5%;
            }
            div{
                ul{
                    list-style-type: none;
                    a{
                        text-decoration: none;
                        font-weight: bold;
                        color: #1C1C1C;
                        font-size: 0.9rem;
                        &:hover{
                            border-bottom: 5px solid #0282f9;
                            padding-bottom: 4rem;
                        }
                    }
                   
                }
            }
        }
    }




</style>