<template>
  <div>
     <b-container class="bv-example-row">
         <b-row class="slj-row">
            <b-col md="3" cols="*">
              <b-card class="slj-card">
                <b-card-text>
                   本项目位于杭州市下城区京都苑18幢。
                </b-card-text>
              </b-card>
            </b-col>
              <b-col md="3" cols="*" >
              <b-card class="slj-card">
                <b-card-text>
                为方便用户的出行需求，响应政府惠民工程，经用户同意为京都苑18幢加装无机房电梯。
                </b-card-text>
              </b-card>
            </b-col>
              <b-col md="3" cols="*">
           <b-card  class="slj-card">
                <b-card-text>
                现状建筑主体结构为框架结构。
                </b-card-text>
              </b-card>
            </b-col>
              <b-col md="3" cols="*">
           <b-card  class="slj-card">
                <b-card-text>
                      <b-img  thumbnail  class="slj-img" :src="imgData[0]" fluid alt="Responsive image"></b-img>
                </b-card-text>
              </b-card>
            </b-col>
         </b-row>
        <b-row class="slj-row">
          <b-col md="3" cols="*">
            <b-card class="slj-card">
              <b-card-text>
                <b-img  thumbnail  class="slj-img" :src="imgData[1]" fluid alt="Responsive image"></b-img>
              </b-card-text>
            </b-card>
          </b-col>
          <b-col md="3" cols="*">
            <b-card class="slj-card">
              <b-card-text>
            楼层数：现状建筑共七层，其中一层与二层为菜市场，三层及以上为办公用房，楼梯通屋顶。
              </b-card-text>
            </b-card>
          </b-col>
          <b-col md="3" cols="*">
          <b-card  class="slj-card">
              <b-card-text>
            电梯井道：原房屋女儿墙标高为26.800，新增电梯顶标高为25.000。
              </b-card-text>
            </b-card>
          </b-col>
            <b-col>
          <b-card  class="slj-card">
              <b-card-text>
                新增一台无机房电梯钢井道工程。
              </b-card-text>
            </b-card>
         </b-col>
        </b-row>
        <b-row class="slj-row">
          <b-col md="3" cols="*">
            <b-card class="slj-card">
              <b-card-text>
               电梯载重量为630kg,井道尺寸为2000mm (宽)×1500mm(深）。
              </b-card-text>
            </b-card>
          </b-col>
          <b-col md="3" cols="*">
            <b-card class="slj-card">
              <b-card-text>
           电梯井道设计总高25m，结构设计使用年限25年。
              </b-card-text>
            </b-card>
          </b-col>
          <b-col md="3" cols="*">
          <b-card  class="slj-card">
              <b-card-text>
            <b-img  thumbnail  class="slj-img" :src="imgData[2]" fluid alt="Responsive image"></b-img>
              </b-card-text>
            </b-card>
          </b-col>
            <b-col md="3" cols="*">
          <b-card  class="slj-card">
              <b-card-text>
           电梯加装占地面积约13.2㎡。
              </b-card-text>
            </b-card>
         </b-col>
        </b-row>
    </b-container>
  </div>
</template>

<script>
import img1 from '../assets/05 (1).jpg'
import img2 from '../assets/05 (2).jpg'
import img3 from '../assets/05 (3).jpg'
export default {
  name: 'Project3',
  data () {
    return {
      imgData: [img1, img2, img3]
    }
  }
}
</script>

<style scoped>
.slj-card{
  height:100%;
}
.slj-img{
  width:100%;
}
.slj-row{
  margin-bottom: 1rem;
}
.slj-img1{
  max-height:8rem;
}
</style>
