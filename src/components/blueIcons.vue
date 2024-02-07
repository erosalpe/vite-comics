<script>
    export default {
        name: "blueIcons"
    }
</script>






<template>
    <div id="blueIconsBg">
        <div class="w-75 m-auto py-5 container-fluid">
            <ul class="d-flex m-0 justify-content-between row">
                <li class="col-2">
                    <a href="#" class="d-flex align-items-center gap-2">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="menuIcon">
                        <span class="text-uppercase">digital comics</span>
                    </a>
                </li>
                <li class="col-2">
                    <a href="#" class="d-flex align-items-center gap-2">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="menuIcon">
                        <span class="text-uppercase">dc merchandise</span>
                    </a>
                </li>
                <li class="col-2">
                    <a href="#" class="d-flex align-items-center gap-2">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="menuIcon">
                        <span class="text-uppercase">subscription</span>
                    </a>
                </li>
                <li class="col-2">
                    <a href="#" class="d-flex align-items-center gap-2">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="menuIcon">
                        <span class="text-uppercase">comic shop locator</span>
                    </a>
                </li>
                <li class="col-2">
                    <a href="#" class="d-flex gap-2 justify-content-center align-items-center p-2">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="menuIcon">
                        <span class="text-uppercase">dc power visa</span>
                    </a>
                </li>
            </ul>
        </div>
    </div>
  


  


</template>








<style scoped>
    #blueIconsBg{
        background-color: #0c7cec;
        div{
            ul{
                list-style-type: none;
                li{
                    a{
                        text-decoration: none;
                        color: white;
                        font-size: 0.8rem;
                        img{
                            width: 25%;
                        }
                    }
                    &:nth-child(4){
                        a{
                            img{
                                width: 15%;
                            }
                        }
                    }
                }
            }
        }
    }




</style>