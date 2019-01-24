 <template>
  <div>
    <section class="hero is-meduim is-info">
      <div class="hero-body">
        <div class="has-text-centered">
          <h1 class="title">Southern Ghana Electricity Consumption -2014</h1>
          <h2 class="subtitle">
            Source:
            <a href>www.come</a>
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
        <div class="column is-12">
          <figure>
            <embed src="~assets/images/charts/Region-by-No.-of-Customers.svg" type>
          </figure>
        </div>
        <hr>
        <div class="column is-12">
          <figure>
            <embed src="~assets/images/charts/Voltage-by-Region.svg" type>
          </figure>
        </div>
        <hr>
        <div class="column is-12">
          <figure>
            <embed src="~assets/images/charts/Voltage-by-MetroMunicipal-Area.svg" type>
          </figure>
        </div>
        <hr>
        <div class="column is-12">
          <figure>
            <embed
              src="~assets/images/charts/Operational-Area-by-No.-Customers-_-Voltage(1).svg"
              type
            >
          </figure>
        </div>
      </div>
      <div v-if="activetab === 2" class="tabcontent">Content for tab two</div>
      <div v-if="activetab === 3" class="tabcontent">Content for tab three</div>
    </div>
  </div>
</template>

<script>
import "vue-tableau";

export default {
  data() {
    return {
      activetab: 1
    };
  }
  // methods: {
  //   initViz: function() {
  //     let viz = new tableau.Viz(this.$refs.tableau1, this.url, this.options);
  //   }
  // },
  // mounted: function() {
  //   this.initViz();
  // }
};
</script>
  

<style scoped>
body {
  background-color: #fff;
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
  background-color: #bedbef;
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