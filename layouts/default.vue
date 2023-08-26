<template>
  <div id="app">
    <HeaderKu />
    <Nuxt />
    <FooterKu />
  </div>
</template>

<script>
// Memanggil component sesuai lokasi masing - masing file
import HeaderKu from '@/components/HeaderKu.vue'
import FooterKu from '@/components/FooterKu.vue'
export default {
  // Dideklarasikan agar dapat diakses oleh template
  components: {
    HeaderKu,
    FooterKu,
  },
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  border: none;
  text-decoration: none;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  color: #e4dfdf;
  background-image: url('../static/sapi1.jpg');
  text-align: center;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  height: 100vh;
  background-position: center;
  position: relative;
}

div .navbar {
  display: inline-block;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  font-size: 85%;
  background-color: rgba(28, 2, 2, 0.9);
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  padding: 1.3%;
  padding-top: 0.7rem;
  padding-bottom: 0.6rem;
  position: fixed;
  z-index: 99;
  border-bottom:0.8px solid #e4dfdf;
}

.a {
  color: #fff;
}

.a:hover {
  color: rgb(110, 8, 8);
}

.container {
  background-color: rgba(44, 44, 45, 0.7);
  text-align: left;
  margin: auto;
  margin-top: 35%;
  padding: 3rem;
  padding-right: 15rem;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
}

.title {
  font-size: 2rem;
  letter-spacing: 1.5px;
}

.container .text {
  text-align: left;
  margin-top: 3px;
  color: #cac7c7;
}

/* footer */
footer {
  background-color: rgb(28, 2, 2);
  position: absolute;
  top: 92vh;
  left: 0;
  right: 0;
  font-size: 85%;
  padding: 1.3%;
  padding-top: 0.6rem;
  padding-bottom: 0.6rem;
  border-top: 0.8px solid #e4dfdf ;
}

.hubungis {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  color: #e4dfdf;
  margin-bottom: 4px;
}


.hubungis .hub{
  color: #e4dfdf;
}

.hubungis .hub:hover {
  color: rgb(110, 8, 8);

}

.hubungis .group svg {
  margin-right: 4px;
}

footer .credit {
  font-size: 9px;
  letter-spacing: 0.8px;
  padding-top: 3px;
  color: #c1bebe;
}

.credit .cre {
  color: #cac7c7;
}

.credit .cre:hover {
  color: rgb(110, 8, 8) ;
}

</style>
