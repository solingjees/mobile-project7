<template>
  <div id="app">
    <Header />
    <Title>采荷路47号加梯</Title>
    <Project1 />
    <Project2>
        <Title>
          <span style="color:#eee">惠都家园</span>
          <template v-slot:line>
            <hr class="my-4" style="border-color:#333;"></hr>
          </template>
        </Title>
    </Project2>
     <Title>京都苑18幢</Title>
     <Project3></Project3>
      <Project4>
        <Title>
          <span style="color:#eee">曙光家园</span>
          <template v-slot:line>
            <hr class="my-4" style="border-color:#333;"></hr>
          </template>
        </Title>
    </Project4>
     <Title>兴和公寓</Title>
     <Project5></Project5>
     <Footer/>
  </div>
</template>

<script>
import Header from './views/Header'
import Project1 from './views/Project1'
import Project2 from './views/Project2'
import Project3 from './views/Project3'
import Project4 from './views/Project4'
import Project5 from './views/Project5'
import Footer from './common/Footer'
import Title from './common/Title'
export default {
  components: {
    Header,
    Project1,
    Project2,
    Project3,
    Project4,
    Project5,
    Title,
    Footer
  }
}
</script>

<style lang="scss">
@font-face {
  font-family: "alibabaFont";
  src: url("./fonts/Alibaba-PuHuiTi-Regular.ttf");
  font-weight: lighter;
}

@font-face {
  font-family: "alibabaFont";
  src: url("./fonts/Alibaba-PuHuiTi-Bold.ttf");
  font-weight: bold;
}

#app {
  font-family: "alibabaFont";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
