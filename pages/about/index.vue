<template>
  <div>
    <section class="container">
      <div class="level columns">
        <div class="level-left column is-half">
          <img src="~/assets/images/team_spirit.svg" width="500px" alt="team">
        </div>
        <div class="level-right column is-half has-text-centered">
          <h1 class="title">About Us</h1>
          <p class="subtitle">
            We live in a data world where the most important resource next to people is data.
            Tones of data are generated dialy in many forms. Most of this data is open source.
            But it is not enough to make data open. To derive insight that will inform decision making, hence making it useful,
            it must be analized and visulaized simple and clear enough for the layman to benefit from it.
            DataGinie is a platform that provides intuitive insights from open source data.
          </p>
        </div>
      </div>
    </section>

    <!-- the team section -->
    <section class="fluid">
      <span class="space"></span>
      <h1 class="title has-text-centered top">The Team</h1>
      <hr class="space container">
      <div class="columns is-12 is-mobile is-multiline is-centered">
        <div class="column is-narrow">
          <figure class="image is-128x128">
            <img class="is-rounded" src="~/assets/images/daniel.svg">
          </figure>
          <br>
          <br>
          <p class="subtitle is-6">Boadzie Daniel.</p>
          <p class="subtitle is-6">Data Scientist |
            <br>Fullstack Developer.
          </p>
          <a>
            <i class="fab fa-github fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-twitter fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-linkedin fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-facebook fa-2x"></i>
          </a>
        </div>
        <div class="column is-narrow">
          <figure class="image is-128x128">
            <img class="is-rounded" src="~/assets/images/joseph.svg">
          </figure>
          <br>
          <br>
          <p class="subtitle is-6">Joseph Akayesi.</p>
          <p class="subtitle is-6">Fullstack Developer |
            <br>Graphic Designer.
          </p>
          <a>
            <i class="fab fa-github fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-twitter fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-linkedin fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-facebook fa-2x"></i>
          </a>
        </div>
        <div class="column is-narrow">
          <figure class="image is-128x128">
            <img class="is-rounded" src="~/assets/images/bruce.svg">
          </figure>
          <br>
          <br>
          <p class="subtitle is-6">Victor-Bruce Crabbe.</p>
          <p class="subtitle is-6">Fullstack Developer |
            <br>UX, UI Developer
          </p>
          <a>
            <i class="fab fa-github fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-twitter fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-linkedin fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-facebook fa-2x"></i>
          </a>
        </div>
        <div class="column is-narrow">
          <figure class="image is-128x128">
            <img class="is-rounded" src="~/assets/images/wonders.svg">
          </figure>
          <br>
          <br>
          <p class="subtitle is-6">Robert Wonders.</p>
          <p class="subtitle is-6">Graphic Designer |
            <br>UX/UI
          </p>
          <a>
            <i class="fab fa-github fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-twitter fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-linkedin fa-2x"></i>
          </a>
          <a>
            <i class="fab fa-facebook fa-2x"></i>
          </a>
        </div>
      </div>
    </section>
  </div>
</template>



<style scoped>
section {
  margin-top: 40px;
  margin-bottom: 40px;
}

.space {
  margin-top: 2rem;
  margin-bottom: 4rem;
}
hr {
  border: 2px solid #5664;
  display: flex;
  justify-content: center;
  align-items: center;
}

.top {
  margin-top: 2rem;
}
</style>
