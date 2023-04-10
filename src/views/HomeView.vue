<template>
  <div class="home">
    <div class="atas">
      <div class="atas-dalam">
        <h1>Apa itu Vue.Js?</h1>
        <p>Vue.js adalah framework JavaScript yang biasa digunakan 
          untuk mengembangkan aplikasi. Biasanya, framework ini
          digunakan untuk dua hal, yaitu membangun User Interface
          (ui) dan Single Page Aplication (SPA).</p>
        </div>
        <img alt="Vue logo" src="../assets/logo.png">
    </div>
    <div class="bawah">
      <h1 class="b-title">Keunggulan Vue.Js</h1>
      <div class="flex-r">
          <p><b>Ukurannya Ringan</b></p>
          <p><b>Mudah Dipahami</b></p>
          <p><b>Dokumntasi Lengkap</b></p>
      </div>
    </div>
  </div>
</template>

<style>

.home {
  text-align: center;
  margin: auto;
  width: 60%;
}
.atas {
  display: flex;
}
.atas-dalam {
  display: flex;
  flex-direction: column;
  text-align: left;

}
.b-title {
  text-align: left;

}
.flex-r {
  display: flex;
  flex-direction: row;
  justify-content: space-between;


}

</style>