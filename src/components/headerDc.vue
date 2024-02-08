<script>
    export default {
        name: "headerDc",
        data() {
            return {
            arrayNavLinks: [
                {
                    name: 'characters',
                    status: false
                },
                {
                    name: 'comics',
                    status: true
                },
                {
                    name: 'movies',
                    status: false
                },
                {
                    name: 'tv',
                    status: false
                },
                {
                    name: 'games',
                    status: false
                },
                {
                    name: 'collectibles',
                    status: false
                },
                {
                    name: 'videos',
                    status: false
                },
                {
                    name: 'fans',
                    status: false
                },
                {
                    name: 'news',
                    status: false
                },
                {
                    name: 'shop',
                    status: false
                },
            ],
            }
        },
        methods: {
            activeControl(){
                
            }
        }
    }
</script>






<template>
    <div id="headerBg">
        <div class="d-flex align-items-center justify-content-between w-75 m-auto">
            <img src="../assets/img/dc-logo.png" alt="Logo">
            <div>
                <ul class="d-flex gap-4">
                    <li v-for="(element,index) in arrayNavLinks">
                        <a href="#" class="text-uppercase"
                        v-bind:class="{'active' : element.status}">{{element.name}}</a>
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
                        /* &:hover{
                            border-bottom: 5px solid #0282f9;
                            padding-bottom: 4rem;
                        } */
                    }
                    a.active{
                        color: #0282f9;
                        border-bottom: 3px solid #0282f9;
                        padding-bottom: 4rem;
                    }
                   
                }
            }
        }
    }

    




</style>