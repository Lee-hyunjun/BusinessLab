<template>
  <div class="mainContent">
    <div>
      <h1>Business area</h1>
      <div class="contentTop">
        <div>
          <div class="image1"></div>
          <div>
            <p>01</p>
            <span>비즈니스 리모델링</span>
          </div>
        </div>
        <div>
          <div class="image2"></div>
          <div>
            <p>02</p>
            <span>비즈니스 리모델링</span>
          </div>
        </div>
        <div>
          <div class="image3"></div>
          <div>
            <p>03</p>
            <span>비즈니스 리모델링</span>
          </div>
        </div>
      </div>
      <div class="contentBottom">
        <div>
          <div class="image4"></div>
          <div>
            <p>04</p>
            <span>비즈니스 리모델링</span>
          </div>
        </div>
        <div>
          <div class="image5"></div>
          <div>
            <p>05</p>
            <span>비즈니스 리모델링</span>
          </div>
        </div>
        <div>
          <div class="image6"></div>
          <div>
            <p>06</p>
            <span>비즈니스 리모델링</span>
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
  .mainContent{
    max-width: 1920px;
    width: 100%;
    height: 800px;
    background-image: url("../assets/backBuilding.png");

    > div{
      margin: 0 auto;
      max-width: 1200px;
      width: 100%;
      
      >h1{
        margin-top: 87px;
        margin-bottom: 50px;
      }

      .contentTop{
        margin-bottom: 48px;
      }

      > div{
        width: 100%;
        height: 235px;
        display: flex;
        align-items: center;
        justify-content: space-between;

        >div{
          height: 100%;
          width: 380px;
          // box-shadow: ;
          box-shadow:3px 10px 20px #d8d8d8;

          > div:first-child{
            height: 151px;
            background:orange ;
          }

          > div:last-child{
            display: flex;
            align-items: center;
            justify-content: flex-start;
            padding-left: 27px;
            height: 85px;
            background: white ;

            p{
             color: #01bc9a; 
             font-size: 26px;
             display: flex;
             align-items: center;
            }

            p::after{
              content: "";
              display: block;
              height: 23px;
              width: 1px;
              background:#5e6480;
              margin:0 10px;
            }
            
            span{
              color: #0d1741;
              font-size: 26px;
            }
          }
        }
      }
    }
  }
</style>>
