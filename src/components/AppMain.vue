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
          <div class="s2-bot-left">
            <div class="s2-bot-left-card">
              <div class="s2-card-top">
                <div class="game1"><img src="../../images/game-img-1.png" alt="" /></div>
                <div class="vs"><img src="../../images/verus-icon.png" alt="" /></div>
                <div class="game2"><img src="../../images/game-img-2.png" alt="" /></div>
              </div>
              <div class="s2-card-mid"></div>
              <div class="s2-card-bot"></div>
            </div>
            <div class="s2-bot-left-card"></div>
          </div>

          <div class="s2-bot-right">
            <div class="s2-bot-right-card"></div>
            <div class="s2-bot-right-card"></div>
          </div>

          <!-- <div class="s2-button">
            <div class="s2-btn">
              <div id="s2btn">
                VIEW ALL MATCH
                <img src="../../images/svg/e-double-right-arrow.svg" alt="" />
              </div>
            </div>
          </div> -->
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
    height: 1730px;
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
      gap: 30px;
      max-width: 75%;
      .s2-bot-left {
        display: flex;
        flex-direction: column;
        gap: 30px;
        .s2-card-top {
          @include spaceAround;
          width: calc((80% / 2) - 30px);
          background-color: $footer-color;
          height: 100px;
          
        }
        .s2-bot-right {
          display: flex;
          flex-direction: column;
          gap: 30px;
        }
      }
    }
  }
}
</style>
