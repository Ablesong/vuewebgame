<template>
    <div class="al">
        <div id="question" v-for="item in data" :key="item">{{item.label}}</div>
    </div>  
</template>

<script>
export default {
  data () {
      return {
           questions: [
            [
                {
                    label:'你走路的时候喜欢靠左侧还是靠右侧？',
    
                }
            ],
            [
                {
                    label:'当你说话时有什么特别的习惯吗？',
                }
            ],
            [
                {
                    label:'你睡觉一般采取怎么样的姿势？',
            
                }
            ],
            [
                {
                    label:'当你说话时有什么特别的习惯吗？',
                }
            ]
        ],
        data: [],
      }
  },
  mounted () {
      this.data = this.questions[0]
  }
}
</script>

<style scoped>
    #question{
        height: 16vh;
        width: 90%;
        margin: 2% 5%;
        font-size: 26px;
        text-align: left;
    }
</style>
