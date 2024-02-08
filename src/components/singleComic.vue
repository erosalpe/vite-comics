<script>
    export default {
        name: "singleComic",
        props: {
            comicImg: String,
            titoloComic: String,
        }
    }
</script>






<template>
    <div class="comicCard">
        <img :src="comicImg" alt="titoloComic">
        <h5>{{ titoloComic }}</h5>
    </div>
</template>








<style scoped>
    .comicCard{
        display: flex;
        flex-direction: column;
        gap: 1rem;
        --gap: 2rem;
        --columns: 6;
        flex-basis: calc((100% / var(--columns)) - var(--gap) + (var(--gap) / var(--columns)));
        img{
            width: 100%;
            aspect-ratio: 1 / 1;
        }
        h5{
            color: white;
            opacity: 0.6;
        }
    }

    




</style>