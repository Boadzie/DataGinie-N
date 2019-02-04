<template>
  <div>
    <section class="container">
      <div class="screen level columns">
        <div class="level-left column is-half">
          <img src="~/assets/images/team_spirit.svg" width="500px" alt="team">
        </div>
        <div class="level-right column is-half">
          <h1 class="title has-text-centered">About Us</h1>
          <p class="is-size-4">
            We live in a data world where the most important resource next to people is data.
            Tones of data are generated daily in many forms. Most of this data is open source.
            To derive <strong>insight that will inform decision making</strong>, data must be analized and visualized.
            <strong>DataGinie is a platform that provides intuitive insights from open source data. 
            We are the first AI/Data Science as a Service company in Ghana.</strong>
          </p>
        </div>
      </div>
    </section>

    <!-- the team section -->
    <section class="fluid top">
      <span class="space"></span>
      <h1 class="title has-text-centered top">The Team</h1>
      <hr class="space container is-6 is-offset-6">
      <div class="columns is-12 is-mobile is-multiline is-centered">
        <div class="column is-narrow">
          <figure class="image is-128x128">
            <img class="is-rounded" src="~/assets/images/daniel.svg">
          </figure>
          <br>
          <br>
          <p class="is-size-5">Boadzie Daniel.</p>
          <p class="is-size-5">Data Scientist |
            <br>Fullstack Developer.
          </p>
          <a href="https://github.com/boadzie" target="_blank">
            <i class="fab fa-github fa-2x"></i>
          </a>
          <a href="https://twitter.com/boadzie" target="_blank">
            <i class="fab fa-twitter fa-2x"></i>
          </a>
          <a href="https://www.linkedin.com/in/daniel-boadzie-5ab68213a/" target="_blank">
            <i class="fab fa-linkedin fa-2x"></i>
          </a>
          <a href="https://www.facebook.com/profile.php?id=100006259099181s" target="_blank">
            <i class="fab fa-facebook fa-2x"></i>
          </a>
        </div>
        <div class="column is-narrow">
          <figure class="image is-128x128">
            <img class="is-rounded" src="~/assets/images/joseph.svg">
          </figure>
          <br>
          <br>
          <p class="is-size-5">Joseph Akayesi.</p>
          <p class="is-size-5">Fullstack Developer |
            <br>Graphic Designer.
          </p>
          <a href="https://github.com/JosephAkayesi" target="_blank">
            <i class="fab fa-github fa-2x"></i>
          </a>
          <a href="https://twitter.com/GHkwamejhosef" target="_blank">
            <i class="fab fa-twitter fa-2x"></i>
          </a>
          <a href="https://www.linkedin.com/in/josephakayesi/" target="_blank">
            <i class="fab fa-linkedin fa-2x"></i>
          </a>
          <a href="https://www.facebook.com/josephakayesi1" target="_blank">
            <i class="fab fa-facebook fa-2x"></i>
          </a>
        </div>
        <div class="column is-narrow">
          <figure class="image is-128x128">
            <img class="is-rounded" src="~/assets/images/bruce.svg">
          </figure>
          <br>
          <br>
          <p class="is-size-5">Victor Bruce-Crabbe.</p>
          <p class="is-size-5">Fullstack Developer |
            <br>UX, UI Developer
          </p>
          <a href="https://github.com/victorbruce" target="_blank">
            <i class="fab fa-github fa-2x"></i>
          </a>
          <a href="https://twitter.com/victorbruce3" target="_blank">
            <i class="fab fa-twitter fa-2x"></i>
          </a>
          <a href="https://linkedin.com/in/victorbruce3" target="_blank">
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
          <p class="is-size-5">Robert Wonders.</p>
          <p class="is-size-5">Graphic Designer |
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
  margin-bottom: 4rem;
}

.space {
  margin-top: 2rem;
  margin-bottom: 4rem;
}
hr {
  border: 2px solid #5664;
  width: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.top {
  margin-top: 4rem;
}

p {
  font-size: 24px !important;
}

strong{
  color:#4876ff;
}

@media only screen and (max-width: 768px) {
  .screen {
   margin: 20px;
  }
}
</style>
