<template>
  <div>
      <div class="img" v-for="item in data" :key="item">{{item.questionImg}}</div>
  </div>
</template>

<script>
export default {
    data () {
        return {
            questionImg:[
            [
                {
                    questionImg:'./img/road.jpg',
    
                }
            ],
            [
                {
                    questionImg:'./img/talk.jpeg',
                
                }
            ],
            [
                {
                    questionImg:'./img/sleep.jpeg',
                
                }
            ],
            [
                {
                    questionImg:'./img/talk.jpeg',   
                }
            ]
        ]
        }
    },
    mounted () {
        this.data = this.questionImg[0]
    }
}
</script>

<style scoped>
    div{
        height: 30vh;
        width: 100vw;
        border: 1px solid sienna;
        margin-bottom: 5%;
    } 
</style>
