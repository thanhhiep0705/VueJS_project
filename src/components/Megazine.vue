<template>
  <div class = "megazine">
    <HeaderComp :header = "header" />
    <ListPost :listPost = "listPost"/>
  </div>
</template>

<script>
import HeaderComp from './Header.vue'
import ListPost from './ListPost.vue';
export default {
    name: "MegazineComp",
    data() {
        return {
            header: "強強強強",
            listPost: [
                {
                    date: "2022.01.01",
                    type: "フショア",
                    title: "強みな ぜベトナムオ. フショア	サービスオフショ アフィールドサ プロセス "
                },
                {
                    date: "2022.01.01",
                    type: "フショア",
                    title: "強みな ぜベトナムオ. フショア	サービスオフショ アフィールドサ プロセス "
                },
                {
                    date: "2022.01.01",
                    type: "フショア",
                    title: "強みな ぜベトナムオ. フショア	サービスオフショ アフィールドサ プロセス "
                },
                {
                    date: "2022.01.01",
                    type: "フシsdgfdgdfgdョア",
                    title: "強みな ぜベトナムオ. フショア	サービスオフショ アフィールドサ プロセス "
                },
                {
                    date: "2022.01.01",
                    type: "フショア",
                    title: "強みな ぜvvベ                                 feeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeトナムオ. フショ        ア	サービスオフショ アフィールドサ プロセス "
                },
            ],
        };
    },
    components: { HeaderComp, ListPost }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cookie&family=Roboto+Condensed:wght@300&display=swap');
.megazine{
    max-width: 1400px;
    margin: auto;
    padding: 5% 10%;
    font-family: 'Cookie', cursive;
font-family: 'Roboto Condensed', sans-serif;
    
}
</style>