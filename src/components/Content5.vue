<template>
  <div class="content5Main">
    <img @click="marker" src="../assets/marker.png" alt="marker">
    <div>
      <div class="textBox">
        <div>
          <p>Contact</p>
          <span style="margin-bottom:20px;">서울특별시 종로구 종로19, 7층 730호 <br> (종로1가, 르메이에르종로타운)</span>
          <span>서울특별시 종로구 종로19, 16층 1622호 <br> (종로1가, 르메이에르종로타운)</span>
          <div></div>
          <span>contact@bizdsnlab.com</span>
          <span>www.facebook.com/bizdsnlab</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  components: {
  },
  methods:{
    marker(){
      location.href = 'http://kko.to/Z4uHoUCDT';
    }
  }
}
</script>

<style lang="scss">

  .content5Main{
    width: 100%;
    height: 524px;
    background-image:url('../assets/content5/map.png');
    display: flex;
    align-items: flex-end;
    justify-content: center;
    position: relative;
    z-index: 1;
    
    >img{
      position: absolute;
      left: 934px;
      top: 174px;
      width: 58px;
      cursor: pointer;
    }

    >div{
      max-width: 1200px;
      width: 100%;
    }

    .textBox{
      max-width: 450px;
      width: 100%;
      height: 320px;
      background: #0d1741;
      padding-top: 48px;

      p{
        color:#01bc9a;
        font-size: 1.5rem;
        margin-bottom: 32px;
        font-family: GmarketSansTTFMedium , sans-serif;
      }

      >div{
        max-width:345px;
        width: 100%;
        margin: 0 auto;

        span:nth-child(4){
          margin-bottom: 15px;
        }


        >div{
          width: 100%;
          height: 1px;
          background: #595960;
          margin-top: 30px;
          margin-bottom: 30px;
        }
      }
      
      span{
        display: block;
        color:#aeaec4;
        font-size: 1rem;
        font-family: GmarketSansTTFMedium , sans-serif;
      }
    }
  }
</style>

