<template>
<div class="all">
  <div class="container">
    <div class="bg_test">
        <div class="bg_test-text">
          who I am       
        </div>
    </div>
  <!-- <img class="d-block w-100" src="./assets/ayano-moregazou.png" data-src="holder.js/900x400?theme=social" alt="First slide"> -->
    <table class="table table-hover">
      <thead>
        <tr>
          <th width="20%">Year</th>
          <th width="20%">What I did</th>
          <th width="60%">Detail</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">2019 9,10,11</th>
          <td>セブIT留学</td>
          <td>大学3年生で大学を１年間休学をして、2019年9月から11月末までの3ヶ月間、フィリピンのセブ島でHTML, CSS, PHPを英語で学ぶプログラミング留学をしました。
            1日10時間勉強を3ヶ月間続け、プログラミングの基礎を叩き込みました。</td>
        </tr>
        <tr>
          <th scope="row">2019 4,5,6,7,8</th>
          <td>
          人材系ベンチャー企業でインターン
          </td>
          <td>大学3年生で大学を１年間休学をして、5ヶ月間ベンチャー企業でインターンをしました。</td>
        </tr>
        <tr>
          <th scope="row">2018 </th>
          <td>
          人材系ベンチャー企業でインターン
          </td>
          <td>大学3年生で大学を１年間休学をして、5ヶ月間ベンチャー企業でインターンをしました。</td>
        </tr>
      </tbody>
    </table>
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