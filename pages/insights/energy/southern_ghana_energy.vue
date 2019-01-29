 <template>
  <div id="container">
    <section class="hero is-meduim is-info">
      <div class="hero-body">
        <div class="has-text-centered">
          <h1 class="title">Electricity Customers in Southern Ghana - 2014</h1>
          <h2 class="subtitle">
            Source:
            <a href="https://energydata.info" target="_blank">
              <em>energydata.info</em>
            </a>
          </h2>
        </div>
      </div>
    </section>
    <div class="tabs container">
      <a v-on:click="activetab=1" v-bind:class="[ activetab === 1 ? 'active' : '' ]">Chart</a>
      <a v-on:click="activetab=2" v-bind:class="[ activetab === 2 ? 'active' : '' ]">Analytics</a>
      <a v-on:click="activetab=3" v-bind:class="[ activetab === 3 ? 'active' : '' ]">Use Case</a>
    </div>

    <div class="content container">
      <div v-if="activetab === 1" class="tabcontent">
        <!-- <div ref="tableau1"></div> -->
        <div class="columns">
          <div class="column is-12">
            <figure>
              <img src="~assets/images/charts/Region-by-No.-of-Customers.svg" type>
            </figure>
          </div>
        </div>
        <hr>
        <div class="column is-12">
          <figure class="image">
            <img src="~assets/images/charts/Voltage-by-Region.svg" type>
          </figure>
        </div>
        <hr>
        <div class="column is-12">
          <figure>
            <img src="~assets/images/charts/Voltage-by-MetroMunicipal-Area.svg" type>
          </figure>
        </div>
        <hr>
        <div class="column is-12">
          <figure>
            <img
              src="~assets/images/charts/Operational-Area-by-No.-Customers-_-Voltage(1).svg"
              type
            >
          </figure>
        </div>
      </div>
      <div v-if="activetab === 2" class="tabcontent">
        <div class="content">
          <h1 class="title">Chart 1</h1>
          <hr>
          <p class="content">
            The first chart show Greater Accra, Ashanti and the Western
            regions as the regions with the largest customer base respectively.
            It also shows the Voltage region as having the least number of customers.
          </p>
          <hr style="margin-bottom:3rem">
        </div>
        <div class="content">
          <h1 class="title">Chart 2</h1>
          <hr>
          <p class="content">
            Even though the first chart showed Greater Accra and the Ashanti regions as the largest
            in terms of customer population than the Western region, the second chart shows the Western region
            as the region with the highest Voltage consumption (264 million Megawatts of energy).
            This may be due to a lot of factors including the presence of large industries with huge energy need in the Western Regions.
          </p>
          <hr style="margin-bottom:3rem">
        </div>
        <div class="content">
          <h1 class="title">Chart 3</h1>
          <hr>
          <p
            class="content"
          >The third chart shows the Metropolitan and Municipal areas and their Voltage consumption in Millions of Megawatts</p>
          <hr style="margin-bottom:3rem">
        </div>
        <div class="content">
          <h1 class="title">Chart 4</h1>
          <hr>
          <p class="content">
            The fouth clearly compared the number of customers in each operational area and their voltage consumption.
            The relationship show non-linearity with some areas with large number of custtomer
            but having low voltage consumption whiles others areas with higher number of customers having significantly lower voltage consumption
          </p>
          <hr style="margin-bottom:3rem">
        </div>
      </div>
      <div v-if="activetab === 3" class="tabcontent">
        <div class="has-text-centered">
          <h1 class="title">Use Cases</h1>
          <p class="subtitle">
            <em>Practical application of insights from data</em>
          </p>
          <hr>
        </div>
        <section class="container columns">
          <div class="column level-left">
            <div class>
              <div class="card-image">
                <figure class="image is-4by3">
                  <img src="~assets/images/government.svg" alt="government">
                </figure>
              </div>
              <div class="card-content">
                <div class="card-title">
                  <h1 class="subtitle">Government</h1>
                </div>
                <div class="content">
                  <p class="content">
                    The insight from the charts will help the government focus on the Western Region,
                    when it comes to taking up public education on the efficient usage of electricity.
                    This is due to its high consumptions rate.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="column level-center">
            <div class>
              <div class="card-image">
                <figure class="image is-4by3">
                  <img src="~assets/images/firms.svg" alt="firms">
                </figure>
              </div>
              <div class="card-content">
                <div class="card-title">
                  <h1 class="subtitle">Firms</h1>
                </div>
                <div class="content">
                  <p class="content">
                    Companies who are into the production, sales and distribution of electrical appliances can rely on this information
                    to sell thier energy efficient products to the Western Region;
                    thus reducing energy consumption rate in the Western region.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="column level-right">
            <div class>
              <div class="card-image">
                <figure class="image is-4by3">
                  <img src="~assets/images/individuals.svg" alt="individuals">
                </figure>
              </div>
              <div class="card-content">
                <div class="card-title">
                  <h1 class="subtitle">Individuals</h1>
                </div>
                <div class="content">
                  <p class="content">
                    This insight will make users of electricity more responsible in thier daily
                    usage of electricity in their various homes,
                    especially people living in the Western Region so as to cut down cost.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </section>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      activetab: 1
    };
  }
};
</script>
  

<style scoped>
body {
  background-color: #fff;
  font-size: 40px;
}
p.content {
  font-size: 18px;
}
#container {
  margin-bottom: 3rem;
}
/* STYLING */

/* Style the tabs */
/* .tabs {
  overflow: hidden;
  margin-left: 20px;
  margin-bottom: -2px;
} */

.tabs ul {
  list-style-type: none;
}

.tabs a {
  float: left;
  cursor: pointer;
  padding: 12px 24px;
  transition: background-color 0.2s;
  border-right: none;
  background-color: beige;
  font-weight: bold;
}

/* Change background color of tabs on hover */
.tabs a:hover {
  background-color: #42aaef;
  color: #fff;
}

/* Styling for active tab */
.tabs a.active {
  background-color: #42aaef;
  color: #fff;
  cursor: default;
}

/* Style the tab content */
.tabcontent {
  padding: 20px;
}
</style>