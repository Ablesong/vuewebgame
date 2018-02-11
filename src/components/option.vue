<template>
    <div class="all">
        <div class="option" v-for="item in data" :key="item">{{item.text}}</div>
    </div>
</template>

<script>
export default {
    data () {
        return {
          
          answers:[
                [
                    {
                        options:'A',
                        text:'左侧',
                        img:''
                    },
                    {
                        options:'B',
                        text:'右侧',
                        img:''
                    },
                    {
                        options:'C',
                        text:'正视对方',
                        img:''
                    },
                    {
                        options:'D',
                        text:'没有特别的习惯',
                        img:''
                    }
                ],      
                [
                    {
                        options:'A',
                        text:'抹下巴',
                        img:''
                    },
                    {
                        options:'B',
                        text:'眼神四处游离',
                        img:''
                    },
                    {
                        options:'C',
                        text:'正视对方',
                        img:''
                    },
                    {
                        options:'D',
                        text:'没有特别的习惯',
                        img:''
                    }
                ], 
                [
                    {
                        options:'A',
                        text:'侧卧',
                        img:''
                    },
                    {
                        options:'B',
                        text:'平躺',
                        img:''
                    },
                    {
                        options:'C',
                        text:'蜷住身体',
                        img:''
                    }     
                ],
                [
                    {
                        options:'A',
                        text:'抹下巴',
                        img:''
                    },
                    {
                        options:'B',
                        text:'眼神四处游离',
                        img:''
                    },
                    {
                        options:'C',
                        text:'正视对方',
                        img:''
                    },
                    {
                        options:'D',
                        text:'没有特别的习惯',
                        img:''
                    }
                ]
        
          ],
          data: [],
        }
    },
  props:[],
  methods:{
 
  },
  mounted () {
      this.data = this.answers[0]
  }
        }

        

</script>

<style scoped>
    [class^="option"]{
        height: 10vh;
        width: 100%;
        margin-bottom: 2%;
        background-color: aquamarine;
        color: white;
        font-size: 24px;
        text-align: center;
        line-height: 74px;
    }
</style>
