<script>
    export default{
        data() {
            return {
                comics: [
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$19.99",
                        "series": "Action Comics",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$3.99",
                        "series": "American Vampire 1976",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$16.99",
                        "series": "Aquaman",
                        "type": "graphic novel"
                    },
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$2.99",
                        "series": "Batgirl",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$3.99",
                        "series": "Batman",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$2.99",
                        "series": "Batman Beyond",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$3.99",
                        "series": "Batman/Superman",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$4.99",
                        "series": "Batman/Superman Annual",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$5.99",
                        "series": "Batman: The Joker War Zone",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$6.99",
                        "series": "Batman: Three Jokers",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$4.99",
                        "series": "Batman: White Knight Presents: Harley Quinn",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://th.bing.com/th/id/OIP.5zQdYxrcDsh0Np37SE8uqgHaLY?pid=ImgDet&rs=1",
                        "price": "$16.99",
                        "series": "Catwoman",
                        "type": "graphic novel"
                    }
                ]
            }
        }    
    }
</script>

<template>
    <div class="jumbotron"></div>
    <div id="current-series">CURRENT SERIES</div>
    <div class="main">
        <div v-for="comic in comics">
            <img v-bind:src="comic.thumb" alt="">
            <div>{{ comic.series }}</div>
        </div>
        <span class="show-button">SHOW MORE</span>
    </div>
</template>

<style lang="scss" scoped>
    #current-series{
        background-color: #0876DC;
        color: white;
        padding: 10px 15px;
        position: absolute;
        left: 250px;
        top: 450px;
    }
    .jumbotron{
        height: 50vh;
        background-image: url(../assets/jumbotron.jpg);
        background-size: cover;
    }
    .main{
        background-color: #1C1C1C;
        padding: 50px 200px;
        color: white;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        div {
            height: 200px;
            width: 16%;
            img{
                width: 80%;
                height: 80%;
            }
            div{
                width: 100%;
            }
        }
        .show-button{   
            background-color: #0876DC;
            color: white;
            padding: 10px 15px;
            margin-top: 40px;
            translate: 500px;
        }
    }
</style>