<template>
  <v-container >
    <div class="appSection">
    <v-row>
      <v-col lg="6">
        <div class="title">
          <h1 class="appSection-title">Be Updated on the go</h1>
          <h1 class= " appSection-subtitle">With our mobile app</h1>
          <v-img
          class="playstore"
            max-height="50"
            max-width="200"
            src="../assets/playstore.png"
          ></v-img>
        </div>
        
      </v-col>
      <v-col lg="6">
        <v-img
          max-height="500"
          max-width="400"
          src="../assets/appImg.png"
        ></v-img>
      </v-col>
    </v-row>
    </div>
  </v-container>
</template>

<script>
export default {
  name: "AppSection",
};
</script>
<style scoped>
.appSection{
  margin-top:0px;
}
h1.appSection-subtitle{
  padding-top: 20px;
  color:#ffb032;
}
.title{
  position: relative; 
  display:block;
  margin-top: 100px;
  font-size: 40px;
}
.playstore{
  position: relative;
  margin-top: 30px;
  align-items: center;
  justify-content: center;
  width: 100%;
  left: 30%;
}
@media only screen and (max-width: 600px) {
h1.appSection-title{
  font-size: 30px;
}
h1.appSection-subtitle{
  font-size: 30px;
}
.playstore{
  left: 15%;
}
}
</style>