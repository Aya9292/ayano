<template>
<div class="all">
  <div class="container">
    <div class="bg_test">
        <div class="bg_test-text">
             Contact 
        </div>
    </div>
      <div class="contact">
        
        <p>お問い合わせはTwitterのDMへ</p>
        <a href="https://twitter.com" class="btn twitter">Twitterで登録</a>
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
.contact{
  padding-bottom: 100px;
}
.twitter{
  background-color:#55acee;
}

</style>
<script>
// @ is an alias to /src

export default {
  name: 'home',
}
</script>
