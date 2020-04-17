<template>
   <div class="slj-box-container">
      <slot></slot>
    <b-container class="bv-example-row">
      <b-row>
        <b-col sm="4" offset-md="2">
            <b-img  thumbnail  class="slj-img" :src="imgData[0]" fluid alt="Responsive image"></b-img>
        </b-col>
        <b-col sm="4">
            <b-img  thumbnail  class="slj-img" :src="imgData[1]" fluid alt="Responsive image"></b-img>
        </b-col>
      </b-row>
      <b-row class="slj-text">
        <b-col md="1" offset-md="2" class="slj-tag-container">
           <div class="num-block">1</div>
        </b-col>
        <b-col md="7" >
          <b-card class="slj-card">
            <b-card-text>
            星桥街道惠都家园多层住宅加装电梯项目，建设内容主要包括惠都24#-26#（地名办2#、6#楼）6 台电梯安装等。
            </b-card-text>
          </b-card>
        </b-col>
      </b-row>

       <b-row class="slj-text">
        <b-col md="1"  order-md="2"  class="slj-tag-container">
           <div class="num-block">2</div>
        </b-col>
        <b-col md="7" order-md="1">
          <b-card class="slj-card">
            <b-card-text>
              该项目住宅1 幢3 个单元，一梯四户，共2 幢楼，6 个单元，有半地下层停非机动车，共六层，层高2.8 米，砖混结构。
            </b-card-text>
          </b-card>
        </b-col>
      </b-row>

       <b-row class="slj-text">
        <b-col md="1" offset-md="2" class="slj-tag-container">
           <div class="num-block">3</div>
        </b-col>
        <b-col md="7" >
          <b-card class="slj-card">
            <b-card-text>
          惠都家园24#-26#（地名办2#、6#楼）楼梯间在北面，加装电梯紧靠原楼梯间，处于公共位置，电梯的自身投影在北侧，对原住宅住户影响少。
            </b-card-text>
          </b-card>
        </b-col>
      </b-row>

      <b-row class="slj-text">
        <b-col md="1"  order-md="2"  class="slj-tag-container">
           <div class="num-block">4</div>
        </b-col>
        <b-col md="7" order-md="1">
          <b-card class="slj-card">
            <b-card-text>
               常规630kg 的电梯井道尺寸为1750mm(宽)×1800mm（深），外框尺寸为2230mm(宽)×2280mm（深）。2#楼加装电梯位置在楼梯间24-J 轴以北的花坛里，现场测量花坛深约2.45 米，6#楼加装电梯位置在楼梯间26-J 轴以北的花坛里，现场测量花坛深约5.5 米，均有条件摆放新加电梯。
            </b-card-text>
          </b-card>
        </b-col>
      </b-row>

        <b-row class="slj-text">
        <b-col md="1" offset-md="2" class="slj-tag-container">
           <div class="num-block">5</div>
        </b-col>
        <b-col md="7" >
          <b-card class="slj-card">
            <b-card-text>
             结合现场考察，原住宅加装电梯具有平层入户的条件，设计将电梯新加连廊与原住宅的公共露台进行连接，实现2-6 层住户均可平层入户。
            </b-card-text>
          </b-card>
        </b-col>
      </b-row>
        <b-row class="slj-text">
        <b-col md="1"  order-md="2"  class="slj-tag-container">
           <div class="num-block">4</div>
        </b-col>
        <b-col md="7" order-md="1">
          <b-card class="slj-card">
            <b-card-text>
               该项目住宅1 幢3 个单元，一梯四户，共2 幢楼，6 个单元，有半地下层停非机动车，共六层，层高2.8 米，砖混结构。
            </b-card-text>
          </b-card>
        </b-col>
      </b-row>
    </b-container>
   </div>
</template>

<script>
import img3 from '../assets/03.jpg'
import img4 from '../assets/04.jpg'
export default {
  name: 'Project2',
  data () {
    return {
      imgData: [
        img3, img4
      ]
    }
  }
}
</script>

<style scoped>
.slj-box-container{
  background-color: #121212;
  line-height: 5rem;
  color:#eee;
}
.slj-img{
  /* height: 20rem !important; */
  margin-bottom: 10px;
}
.slj-card{
   border-bottom-color: #232323;
   background-color: transparent;
   line-height: 1.5rem;
   max-width: 44rem;
}
.slj-text{
  display: flex;
  justify-content: center;
  align-items: center;
}
.num-block{
  height: 3rem;
  background-color: #254dff;
  width:3rem;
  text-align: center;
  line-height: 3rem;
  margin:0px !important;
}
.slj-tag-container{
  display:flex;
  justify-content: center;
}
</style>
