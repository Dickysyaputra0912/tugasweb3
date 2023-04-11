<template>
  <!--banner image-->

  <div class="banner-image w-100 vh-100 d-flex justify-content-center align-items-center">
    <div  class="images">
      <div class="profile">
        <img src="https://o.remove.bg/downloads/d91abece-fbd1-4952-94aa-bff3c8c8d4dc/WhatsApp_Image_2023-04-11_at_23.39.46-removebg-preview.png" class="rounded-circle"
             height="300px" width="300px">
      </div>
      <div class="content text-center">
        <h1 class="text-white">Muhamamd Khalil Gibran</h1>
        <h2>Selamat Datang</h2>
      </div>
    </div>
  </div>


</template>

<script>
export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
.text-center{
  margin-top: 50px;
}
.images {
  margin-top: -400px;
}
.banner-image{
  background: #282828;
  background-size: cover;
}


</style>
