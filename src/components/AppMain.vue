<script>
export default {
  data() {},
};
</script>

<template>
  <main>
    <div class="container">
      <section>
        <div class="s1-left">
          <img src="../../images/features-illus.png" alt="" />
        </div>
        <div class="s1-right">
          <div class="s1-right-top">
            <h4>The ultimate Competitive Gaming Platform</h4>
            <h2>Make Your Mark On The Battle Field</h2>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla
              vero voluptates aliquid consectetur culpa, facere repellat tempora
              ea
            </p>
          </div>
          <div class="s1-right-bot">
            <div class="s1-right-bot-left">
              <ul>
                <li>
                  <img src="../../images/icon/features-icon-1.png" alt="" />
                </li>
                <li>
                  <img src="../../images/icon/features-icon-2.png" alt="" />
                </li>
                <li>
                  <img src="../../images/icon/features-icon-3.png" alt="" />
                </li>
              </ul>
            </div>

            <div class="s1-right-bot-right">
              <ul>
                <li>
                  <h4>Live Streaming</h4>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Veritatis iusto eaque nobis dicta minus officia veniam est
                  </p>
                </li>
                <li>
                  <h4>Great Tournament</h4>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Veritatis iusto eaque nobis dicta minus officia veniam est
                  </p>
                </li>
                <li>
                  <h4>Gaming News</h4>
                  <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    Veritatis iusto eaque nobis dicta minus officia veniam est
                  </p>
                </li>
              </ul>
            </div>
          </div>
          <div class="s1-button">
            <div class="s1-btn">
              <div id="s1-btn">
                PLAY NOW
                <img src="../../images/svg/e-double-right-arrow.svg" alt="" />
              </div>
            </div>
          </div>
        </div>
      </section>
      <section>

        <div class="s2-top">
          <h4>Trending Battle</h4>
          <h2>Keep Eyes & Manage upcoming Battle</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia saepe
            voluptatibus fugit temporibus obcaecati eligendi dicta. Corporis
            voluptate
          </p>
        </div>

        <div class="s2-bot">
          <div class="s2-bot-card">
            <div class="s2-bot-card-top">
              <img src="../../images/game-img-1.png" alt="">
              <img src="../../images/verus-icon.png" alt="">
              <img src="../../images/game-img-2.png" alt="">
            </div>
            <div class="s2-bot-card-mid">
              <h4>Call Of Deauty</h4>
              <h5>December 25, 2022 4:00 PM</h5>
            </div>
            <div class="s2-bot-card-bot">
              <img src="../../images/icon/youtube-icon.png" alt="">Youtube             
              <img src="../../images/icon/twitch-icon.png" alt="">Twitch         
            </div>
          </div>
          <div class="s2-bot-card">
            <div class="s2-bot-card-top">
              <img src="../../images/game-img-3.png" alt="">
              <img src="../../images/verus-icon.png" alt="">
              <img src="../../images/game-img-4.png" alt="">
            </div>
            <div class="s2-bot-card-mid">
              <h4>Legendary Battles</h4>
              <h5>December 25, 2022 4:00 PM</h5>
            </div>
            <div class="s2-bot-card-bot">
              <img src="../../images/icon/youtube-icon.png" alt="">Youtube             
              <img src="../../images/icon/twitch-icon.png" alt="">Twitch         
            </div>
          </div>
          <div class="s2-bot-card">
            <div class="s2-bot-card-top">
              <img src="../../images/game-img-5.png" alt="">
              <img src="../../images/verus-icon.png" alt="">
              <img src="../../images/game-img-6.png" alt="">
            </div>
            <div class="s2-bot-card-mid">
              <h4>Nay Corral Gundown</h4>
              <h5>December 25, 2022 4:00 PM</h5>
            </div>
            <div class="s2-bot-card-bot">
              <img src="../../images/icon/youtube-icon.png" alt="">Youtube             
              <img src="../../images/icon/twitch-icon.png" alt="">Twitch         
            </div>
          </div>
          <div class="s2-bot-card">
            <div class="s2-bot-card-top">
              <img src="../../images/game-img-7.png" alt="">
              <img src="../../images/verus-icon.png" alt="">
              <img src="../../images/game-img-8.png" alt="">
            </div>
            <div class="s2-bot-card-mid">
              <h4>League Of Legends</h4>
              <h5>December 25, 2022 4:00 PM</h5>
            </div>
            <div class="s2-bot-card-bot">
              <img src="../../images/icon/youtube-icon.png" alt="">Youtube             
              <img src="../../images/icon/twitch-icon.png" alt="">Twitch         
            </div>
          </div>
        </div>

        <div class="s2-button">
            <div class="s2-btn">
              <div id="s2-btn">
                VIEW ALL MATCH
                <img src="../../images/svg/e-double-right-arrow.svg" alt="" />
              </div>
            </div>
          </div>

      </section>
      <section>

      <h2>Futio Quick Facts</h2>

      <div class="s3-boxes">

      <div class="s3-box">
        <span>1135</span>
        <h4>Twitch Streams</h4>
      </div>
      <div class="s3-box">
        <span>44</span>
        <h4>Total Games</h4>
      </div>
      <div class="s3-box">
        <span>982</span>
        <h4>YouTube Streams</h4>
      </div>
      <div class="s3-box">
        <span>40</span>
        <h4>Pro Team</h4>
      </div>

    </div>

      </section>
    </div>
  </main>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables.scss" as *;
@use "../styles/partials/mixins.scss" as *;

.container {
  width: 100%;

  section:nth-child(1) {
    height: 865px;
    width: 100%;
    background-color: $secondary-color;
    display: flex;
    align-items: center;

    .s1-left {
      width: 50%;

      img {
        width: 90%;
        margin-left: -50px;
      }
    }

    .s1-right {
      width: 35%;

      h4 {
        font-size: 30px;
        color: $primary-color;
        margin-right: 90px;
      }

      h2 {
        font-size: 65px;
        color: $text-color;
        margin-top: 10px;
      }

      p {
        color: $underText-color;
        margin-top: 10px;
        font-size: 18px;
      }

      .s1-right-bot {
        display: flex;
        gap: 30px;

        .s1-right-bot-left {
          img {
            display: block;
            margin-top: 40px;
          }
        }

        .s1-right-bot-right {
          h4 {
            color: $text-color;
            margin-top: 25px;
          }

          ul li {
            text-decoration: none;
          }
        }
      }

      .s1-button {
        margin-top: 50px;

        .s1-btn {
          width: 125px;
          height: 50px;
          border: 1px solid $button-color;
          border-radius: 20px;
          @include center;
        }

        #s1-btn {
          width: 115px;
          height: 40px;
          border-radius: 20px;
          color: $secondary-color;
          background-color: $button-color;
          text-align: center;
          line-height: 40px;
          z-index: 1;

          &:hover {
            cursor: pointer;
            background-color: $primary-color;
          }
        }
      }
    }
  }
  section:nth-child(2) {
    height: 1530px;
    width: 100%;
    background-color: $bkground-color;

    .s2-top {
      max-width: 35%;
      margin: auto;
      padding-top: 100px;
      text-align: center;
      h4 {
        font-size: 30px;
        color: $primary-color;
        margin-right: 90px;
      }

      h2 {
        font-size: 65px;
        color: $text-color;
        margin-top: 10px;
      }

      p {
        color: $underText-color;
        margin-top: 15px;
        font-size: 18px;
      }
    }

    .s2-bot {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
      gap: 30px;
      width: 80%;
      margin: auto;
      margin-top: 65px;
      .s2-bot-card {
        height: 450px;
        width: calc((80% / 2) - 5px );
        background-color: $footer-color;
        border-radius: 20px;
        .s2-bot-card-top {
          height: 46%;
          width: 100%;
          @include spaceAround;
          
        }
        .s2-bot-card-mid {
          height: 27%;
          width: 100%;
          background-color: $card-color;
          text-align: center; 
          h4 {
            font-size: 25px;
            padding-top: 25px;
            color: $text-color;
          }
          h5 {
            padding-top: 20px;
            font-size: 15px;
            color: $primary-color;
          }
        }
        .s2-bot-card-bot {
          height: 27%;
          width: 100%;
          @include center;
          color: $text-color;
          img:hover {
            cursor: pointer;
          }
          img:nth-child(2) {
            margin-left: 25px          
          }
        }
      }
    }
    .s2-button {
      @include center;
      margin-top: 60px;
      .s2-btn {
          width: 200px;
          height: 50px;
          border: 1px solid $button-color;
          border-radius: 20px;
          @include center;
        }

        #s2-btn {
          width: 180px;
          height: 40px;
          border-radius: 20px;
          color: $secondary-color;
          background-color: $button-color;
          text-align: center;
          line-height: 40px;
          z-index: 1;

          &:hover {
            cursor: pointer;
            background-color: $primary-color;
          }
        }
    }
  }
  section:nth-child(3) {
    background-color: $secondary-color;
    height: 380px;
    width: 100%;
    display: flex;
    text-align: center;
    flex-direction: column;
    h2 {
      color: $text-color;
      padding-top: 70px;
      font-size: 45px;
    }
    .s3-boxes {
      width: 66%;
      @include center;
      align-self: center;
      margin-top: 50px;
      gap: 20px;
      .s3-box {
      width: calc((66% / 4) - 20px);
      height: 125px;
      border: 0.5px solid rgb(202, 200, 200, .2);
      border-radius: 20px;
      @include center;
      flex-direction: column;
      
      span {
        color: $text-color;
        font-size: 35px;
      }
      h4 {
        color: $primary-color;
        font-size: 11px;
        opacity: 0.5;
        margin-top: 5px;
        
      }

    }
    }
    
  }
}

</style>
