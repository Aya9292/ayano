<template>
<div class="all">
  <div class="container">
    <div class="bg_test">
        <div class="bg_test-text">
            I am Ayano Nakamura
        </div>
    </div>

    <div class="card-deck">
      <div class="card mb-4">
        <div class="card-body">
          <h4 class="card-title">HTML&CSS</h4>
          <a class="text-secondary" href="https://ayano-profile-page.herokuapp.com/">My Profile</a><br>
          <a class="text-secondary" href="http://127.0.0.1:8000/home">CEBU Pizza</a>
          

        </div>
      </div>
      <div class="card mb-4">
        <div class="card-body">
          <h4 class="card-title">PHP</h4>
          <a class="text-secondary" href="http://localhost:8001/">To do List</a><br>
          <a class="text-secondary"  href="http://localhost:8003/">Awesome Blog</a>
        </div>
      </div>
      <div class="card mb-4">
        <div class="card-body">
          <h4 class="card-title">JavaScript</h4>
          <a class="text-secondary"  href="file:///Users/ayanonakamura/Desktop/vue/index.html">Pizza Order Form</a>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<style>
.all{
  background-image: url(../assets/pastel.jpeg);
    background-size: cover;
}
.bg_test-text {                      
    display:  inline-block;                         /* インラインブロックにする */
    padding: 10px 20px;                             /* 余白指定 */
    background-color: rgba(255, 255, 255, 0.7);     /* 背景色指定 */
}
.bg_test {
    text-align:  center;    /* 文字中央寄せ */
    padding:  150px;        /* 余白指定 */
   
}

</style>
<script>
// @ is an alias to /src

export default {
  name: 'home',
}
</script>
