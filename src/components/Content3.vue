<template>
  <div class="content3Main">
    <div>
      <div class="fonts">
        <p>Our Goal</p>
        <span>With more than 20 years of know-how,<br>we will be your business success partner.</span>
      </div>
      <div class="contentBox">
        <div>
          <div class="boxItem">
            <div>
              <div class="icon1" alt="icon1"></div>
              <p>Analysis</p>
            </div>
            <p>기업 전체의 비즈니스를 한 눈에 볼 수 있게 <br> 함으로써 기업내의 자원과 노력을 효과적으로 <br> 배분할 수 있게 합니다.</p>
          </div>
          <div class="boxItem">
            <div>
              <div class="icon2" alt="icon2"></div>
              <p>Optimization</p>
            </div>
            <p></p>
          </div>
        </div>
        <div>
          <div class="boxItem">
            <div>
              <div class="icon3" alt="icon3"></div>
              <p>Insight</p>
            </div>
            <p>현재를 위한 사업 최적화, 내일을 위한 사업기회 <br> 발굴 등 균형을 맞출 수 있게 합니다.</p>
          </div>
          <div class="boxItem">
            <div>
              <div class="icon4" alt="icon4"></div>
              <p>Know-how</p>
            </div>
            <p></p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style lang="scss">
  @font-face{
    font-family: GmarketSansTTFMedium;
    src : "../assets/fonts/GmarketSansTTF/GmarketSansTTFMedium.ttf";
    font-weight : '400';
  }

  .content3Main{
    width: 100%;
    height: 627px;
    background-image: url("../assets/content3/back.png");
    padding-top: 69px;

    >div{
      margin: 0 auto;
      max-width: 1200px;
      width: 100%;
      display: flex;
      align-items: flex-start;
      justify-content: space-between;
    }

    .fonts{

      p,span{
        font-family : GmarketSansTTFMedium !important;
        color: #0d1741;
        font-weight: bold;
      }

      p{
        font-size: 2.375rem;
      }

      span{
        font-size: .625rem;
      }
    }
    
    .contentBox{
      max-width: 790px;
      width: 100%;
      >div{
        width: 100%;
        position: relative;
        display: flex;
        align-items: center;
      }

      .boxItem{
        max-width: 395px;
        width: 100%;
        height: 175px;
        background: #101a44;
        border: 1px solid #212c57;
        display: flex;
        // align-items: center;

        >div{
          display: flex;

          >div{
            margin-right: 20px; 
            width: 35px;
            height: 35px;
            // position: absolute;
            background-repeat: no-repeat;
            
          }

          .icon1{background-image:url('../assets/content3/icons/icon1.png')}
          .icon2{background-image:url('../assets/content3/icons/icon2.png')}
          .icon3{background-image:url('../assets/content3/icons/icon3.png')}
          .icon4{background-image:url('../assets/content3/icons/icon4.png')}

          p{
            color: white;
            font-size: 1.5rem;
          }
        }
      }
    }
  }
</style>
