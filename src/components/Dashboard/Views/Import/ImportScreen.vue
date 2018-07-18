<template>
  <div class="content">
    <div class="container-fluid">
      <div class="row">
        <div v-for = "image in images" class ="col-md-4 mt-2-5">
          <img :src="image.src" class="medium-sized">
        </div>
      </div>
    </div>
  </div>
</template>
<script>

export default {
  components: {

  },
  data () {
    return {
      images:[
        {src:'http://www.arrl.org/images/view/TIS/PowerLineNoise/Intro_lrg.jpg'},
        {src:'https://static.utilityweek.co.uk/artimg/1396632_Broken-pylon-snow.jpg'},
        {src:'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfhwqNv4hv0Nr3WJTbf5rs5YYTZIk7A0rtRMtba_rkEEdfpC0O'},
        {src:'https://www.xcelenergy.com/staticfiles/xe-responsive/assets/images/3%20Tile/Xcel-Energy-Transmission-Line-3Tile-768x420.jpg'}
    ]
    }
  },
  methods: {

  }
}

</script>
<style scoped>
.medium-sized{
  height: 250px;
  width: 250px;
}
.mt-2-5{
  margin-top: 2.5% !important;
}

</style>
