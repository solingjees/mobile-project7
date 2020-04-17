/* eslint-disable no-unused-vars */
<template>
  <div>
    <b-container>
      <b-row class="slj-row-container">
        <b-col class="slj-img-container">
           <b-img  thumbnail  class="slj-img" :src="imgData[0]" fluid alt="Responsive image"></b-img>
        </b-col>
        <b-col md="9">
         <b-card class="slj-card">
            <b-card-text>
            本项目位于杭州市江干区采荷路47号4幢1单元，为中华全国供销合作总社杭州茶叶研究院宿舍。周边环境优美，生活设施丰富，交通便利，四通八达。
            </b-card-text>
         </b-card>
         <b-card class="slj-card">
            <b-card-text>
            为照顾老人、小孩和腿脚不方便人士，响应政府惠民工程，经住户同意，现为采荷路47号4幢1单元加装无机房电梯。
            </b-card-text>
         </b-card>
         <b-card class="slj-card">
            <b-card-text>
            原结构类型为框架结构
            </b-card-text>
         </b-card>
           <b-card class="slj-card">
            <b-card-text>
           原建筑一层为营业用房、自行车库，以上为住宅， 共七层，上部标准层层高2.900m,一层3.600m。
            </b-card-text>
         </b-card>
        </b-col>
      </b-row>
       <b-row class="slj-row-container">
        <b-col  order-md="2"  class="slj-img-container">
           <b-img  thumbnail  class="slj-img" :src="imgData[1]" fluid alt="Responsive image"></b-img>
        </b-col>
        <b-col cols="*" order-md="1" col-md="9">
         <b-card class="slj-card">
            <b-card-text>
         井道设计总高度22.170m。原房屋檐口标高21.570m,新增电梯顶标高21.600m。
            </b-card-text>
         </b-card>
         <b-card class="slj-card">
            <b-card-text>
          本项目为采荷路47号4幢1单元新增1台东南品牌豌豆电梯钢井道一体式工程。
            </b-card-text>
         </b-card>
         <b-card class="slj-card">
            <b-card-text>
         电梯为630kg，井道尺寸为1800mm（深）×1900mm（宽）。
            </b-card-text>
         </b-card>
           <b-card class="slj-card">
            <b-card-text>
          本项目标高从-1.335m~21.600m,建筑总高度22.935m,本结构设计使用年限为25年。
            </b-card-text>
         </b-card>
          <b-card class="slj-card">
            <b-card-text>
           加装电梯项目中，电梯占地面积4.51㎡，封闭连廊建筑面积1.29㎡，新增建筑面积34.8㎡。
            </b-card-text>
         </b-card>
        </b-col>

      </b-row>
    </b-container>
  </div>
</template>

<script>
// eslint-disable-next-line no-unused-vars
import img1 from '../assets/01.jpg'
import img2 from '../assets/02.jpg'
export default {
  name: 'Project1',
  data () {
    return {
      imgData: [
        img1, img2
      ]
    }
  }
}
</script>

<style scoped>
.slj-img-container{
  flex-direction: row;
  justify-content: center;
  display: flex;
}

.slj-img{
  max-height: 20rem !important;
  margin: auto auto;
}
.slj-card{
  margin-top:10px;
  text-align: left;
}
.slj-row-container{
  margin-bottom:40px;
}
</style>
