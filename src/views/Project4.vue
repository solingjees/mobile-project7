<template>
 <div class="slj-box-container">
      <slot></slot>
          <b-container>
      <b-row class="slj-row-container">
        <b-col class="slj-img-container">
           <b-img  thumbnail  class="slj-img" :src="imgData[0]" fluid alt="Responsive image"></b-img>
        </b-col>
        <b-col md="9">
         <b-card class="slj-card">
            <b-card-text>
             本项目位于杭州市余杭区临平曙光嘉园嘉丰苑1幢1单元。周边环境优美，生活设施丰富，交通便利，四通八达。
            </b-card-text>
         </b-card>
         <b-card class="slj-card">
            <b-card-text>
            为照顾老人、小孩和腿脚不方便人士，响应政府惠民工程，经住户同意，现为临平曙光嘉园嘉丰苑1幢1单元加装无机房电梯。
            </b-card-text>
         </b-card>
         <b-card class="slj-card">
            <b-card-text>
            原结构类型为框架结构
            </b-card-text>
         </b-card>
           <b-card class="slj-card">
            <b-card-text>
           楼层数：6层，原建筑一至二层为营业用房，层高约3.750m；三至六层为住宅，层高为2.800m。
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
          电梯井道：井道设计总高度18.590m,原房屋檐口标高约19.300m，新增电梯顶标高19.120m。
            </b-card-text>
         </b-card>
         <b-card class="slj-card">
            <b-card-text>
           新增一台奥的斯机电无机房电梯钢架梁井道工程。
            </b-card-text>
         </b-card>
         <b-card class="slj-card">
            <b-card-text>
           电梯为550kg，井道净尺寸1300mm（深）×2100mm（宽）。
            </b-card-text>
         </b-card>
           <b-card class="slj-card">
            <b-card-text>
          本项目标高从-1.120m~18.520m,建筑总高度19.640m,本结构设计使用年限为25年。
            </b-card-text>
         </b-card>
          <b-card class="slj-card">
            <b-card-text>
           加装电梯项目中，电梯占地面积4.68㎡，封闭连廊建筑面积12.06㎡，新增建筑面积38.16㎡。
            </b-card-text>
         </b-card>
        </b-col>

      </b-row>
    </b-container>
 </div>
</template>

<script>
import img1 from '../assets/6 (1).jpg'
import img2 from '../assets/6 (2).jpg'
export default {
  name: 'Project4',
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
.slj-box-container{
  background-color: #121212;
  line-height: 1rem;
  color:#eee;
}
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
  background-color: transparent;
}
.slj-row-container{
  margin-bottom:40px;
}
</style>
