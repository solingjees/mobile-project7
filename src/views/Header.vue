<template>
   <div>
  <b-navbar class="slj-navbar" toggleable="lg" type="dark">
    <b-navbar-brand class="slj-navbar-brand" href="#">solingjees设计院</b-navbar-brand>
  </b-navbar>
   <b-jumbotron class="slj-jumbotron" header-level="4">
    <template v-slot:header>2019工程项目统览</template>
     <template v-slot:lead>
       <span class="slj-jumbotron-lead-word">采荷路47号加梯</span> /  <span class="slj-jumbotron-lead-word">惠都家园</span> /  <span class="slj-jumbotron-lead-word">京都苑18幢</span> /  <span class="slj-jumbotron-lead-word">曙光嘉园嘉丰苑</span> /  <span class="slj-jumbotron-lead-word">兴和公寓15幢4</span>
    </template>
  </b-jumbotron>
</div>
</template>

<script>
export default {
  name: 'header'
}
</script>

<style>
.slj-navbar{
  background-color: transparent !important;
  z-index: 100;
  box-sizing: content-box;
  max-width: 1000px;
  margin: auto;
  color:#eee;
}
.slj-navbar-brand{
      font-size: 1rem !important;
}
.slj-jumbotron-lead-word{
  font-size: 1.5rem;
}
.slj-jumbotron{
  color:#eee;
  position: relative;
  height: 500px;
  top: -56px;
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: auto 100%;
  background-color: black !important;
  background-image: url("../assets/jubron.jpg");
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-bottom: 0px !important;
}
</style>
