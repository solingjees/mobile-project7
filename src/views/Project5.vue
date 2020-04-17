<template>
  <div>
      <b-container class="bv-example-row" v-for="con in [0,1,2]" :key="con">
      <b-row class="slj-img-row">
        <b-col sm="3" v-for="item in [0+con*4 ,1+con*4,2+con*4,3+con*4]" :key="item">
            <b-img  thumbnail  class="slj-img" rounded :src="imgData[item]" fluid alt="Responsive image"></b-img>
        </b-col>
      </b-row>
      <b-row>
          <b-col>
          <b-card class="slj-card" v-for="item in [0+con*3,1+con*3,2+con*3]"  :key="item">
            <b-card-text>
              {{text[item]}}
            </b-card-text>
         </b-card>
        </b-col>
      </b-row>
      </b-container>
  </div>
</template>
<script>
import img1 from '../assets/7 (1).jpg'
import img2 from '../assets/7 (2).jpg'
import img3 from '../assets/7 (3).png'
import img4 from '../assets/7 (4).jpg'
import img5 from '../assets/7 (5).png'
import img6 from '../assets/7 (6).jpg'
import img7 from '../assets/7 (7).png'
import img8 from '../assets/7 (8).jpg'
import img9 from '../assets/7 (9).jpg'
import img10 from '../assets/7 (10).jpg'
import img11 from '../assets/7 (11).jpg'
import img12 from '../assets/7 (12).jpg'
import img13 from '../assets/7 (13).jpg'
export default {
  name: 'Project5',
  data () {
    return {
      imgData: [img1, img2, img3, img4, img5, img6, img7, img8, img9, img10, img11, img12, img13],
      text: [
        '本项目位于杭州市下城区兴和公寓15幢4单元。周边环境优美，生活设施丰富，交通便利，四通八达。',
        '为照顾老人、小孩和腿脚不方便人士，响应政府惠民工程，经住户同意，现为兴和公寓15幢4单元加装无机房电梯。',
        '原结构类型：砖混结构',
        '楼层数：原建筑一层为营业用房、以上为住宅，共七层，上部标准层层高2.800m，一层4.030m。',
        '电梯井道：原房屋檐口标高约21.430m，新增电梯顶标高约21.250m。',
        '本项目为兴和公寓15幢4单元新增一台奥的斯机电无机房电梯钢架梁井道工程。',
        '电梯为550kg，井道净尺寸1300mm（深）×2100mm（宽）。',
        '本项目标高从-1.230m~21.250m,建筑总高度22.480m,本结构设计使用年限为25年。',
        '加装电梯项目中，电梯占地面积4.68㎡，开敞连廊建筑面积3.06㎡，新增建筑面积27.9㎡。'
      ]
    }
  }
}
</script>

<style scoped>
.slj-img{
  height: 10rem !important;
}
.slj-card{
  margin-top:10px;
  text-align: left;
  margin-top: 10px;
}
.slj-img-row{
  margin-top: 10px;
}
</style>
