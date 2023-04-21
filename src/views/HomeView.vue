<script></script>

<template>
  <div class="home">
    <div class="feature-card">
      <router-link to="/movie/tt0409591">
        <img
          src="https://occ-0-325-58.1.nflxso.net/dnm/api/v6/6AYY37jfdO6hpXcMjf9Yu5cnmO0/AAAABS6v2gvwesuRN6c28ZykPq_fpmnQCJwELBU-kAmEcuC9HhWX-DfuDbtA-bfo-IrfgNtxl0qwJJlhI6DENsGFXknKkjhxPGTV-qhp.jpg?r=608"
          alt="Stranger Things Poster"
          class="featured-img" />
        <div class="detail">
          <h3>Stranger Things</h3>
          <p>
            Stranger Things is set in the fictional rural town of Hawkins,
            Indiana, in the 1980s. The nearby Hawkins National Laboratory
            ostensibly performs scientific research for the United States
            Department of Energy but secretly experiments with the paranormal
            and supernatural, sometimes with human test subjects.
          </p>
        </div>
      </router-link>
    </div>
  </div>
</template>

<style lang="scss">
.home {
  .feature-card {
    position: relative;

    .featured-img {
      display: block;
      width: 100%;
      height: 300px;
      object-fit: cover;

      position: relative;
      z-index: 0;
    }

    .detail {
      position: absolute;
      left: 0;
      right: 0;
      bottom: 0;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 16px;
      z-index: 1;
    }
  }
}
</style>
