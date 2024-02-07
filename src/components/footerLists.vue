<script>
    export default {
        name: "footerLists"
    }
</script>






<template>
    <div id="footerListsBg">
        <div class="w-75 m-auto py-4 overflow-hidden">
            <div class="d-flex gap-3">
                <div>
                    <ul>
                        <li class="titleLi text-uppercase">
                            <span>dc comics</span>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">characters</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">comics</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">movies</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">TV</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">games</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">videos</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">news</a>
                        </li>
                        <li class="titleLi text-uppercase">
                            <span>shop</span>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">shop DC</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">shop DC collectibles</a>
                        </li>
                    </ul>
                </div>
                <div>
                    <ul>
                        <li class="titleLi text-uppercase">
                            <span>dc</span>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">terms of use</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">privacy policy (new)</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">ad choices</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">advertising</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">jobs</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">subscriptions</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">talent workshops</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">CPSC certificates</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">ratings</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">shop help</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">contact us</a>
                        </li>
                    </ul>
                </div>
                <div>
                    <ul>
                        <li class="titleLi text-uppercase">
                            <span>sites</span>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">DC</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">MAD magazine</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">DC kids</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">DC universe</a>
                        </li>
                        <li class="text-capitalize">
                            <a href="#">DC visa</a>
                        </li>
                    </ul>
                </div>
            </div>

            <div id="dcBgLogo">
                <img src="../assets/img/dc-logo-bg.png" alt="dcLogo">
            </div>

            
        </div>

    </div>
  


  


</template>








<style scoped>
    #footerListsBg{
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        div{
            position: relative;
            ul{
                .titleLi{
                    color: white;
                    font-weight: bold;
                    font-size: 1.2rem;
                    margin-block: 1rem;
                }

                list-style-type: none;
                a{
                    text-decoration: none;
                    color: white;
                    font-size: 0.8rem;
                    opacity: 0.7;
                }
                   
            }

            #dcBgLogo{
                position: absolute;
                top: -50px;
                right: 0;

            }
            
        }
    }
    




</style>