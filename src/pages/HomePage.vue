<script setup>


</script>

<template>
  <div class="container">
    <div class="row">
      <div class="col-12">
        <div
             class="d-flex justify-content-between align-items-center flex-column flex-md-row px-2 mt-3 bg-light bg-opacity-75 shadow-lg rounded">
          <div class="d-flex gap-3 fs-3">
            <span class="mdi mdi-vuejs text-vue"></span>
            <span class="mdi mdi-language-javascript text-yellow"></span>
            <span class="mdi mdi-language-csharp text-green"></span>
            <span class="mdi mdi-dot-net text-purple"></span>
          </div>
          <div class="p-2 text-center">
            <span class="fs-5">Full-Stack Software Developer</span>
            <h1 class="display-4 mb-0">Dallin Hooper</h1>
          </div>
          <div class="d-flex gap-3 fs-3">
            <span class="mdi mdi-nodejs text-success"></span>
            <span class="mdi mdi-language-html5 text-orange"></span>
            <span class="mdi mdi-language-css3 text-indigo"></span>
            <span class="mdi mdi-database text-warning"></span>
          </div>
        </div>
      </div>
    </div>
    <div class="row mt-3">
      <div class="col-md-6">
        <div class="d-flex flex-column justify-content-evenly h-100 bg-light rounded about">
          <div>
            <h2 class="text-center mb-0">About</h2>
          </div>
          <div class="px-5">
            <p class="mb-0 fs-4">My journey into the tech world began as a support engineer for an online mortgage
              service platform. I worked with developers to identify, troubleshoot, and improve the user experience.
              Seeking to improve myself, I have fostered my own development knowledge through personal studies and both
              collegiate and
              professional certifications.</p>
          </div>
          <div></div>
        </div>
      </div>
      <div class="col-md-6">
        <div class="rounded">
          <img src="@/assets/img/IMG_8314.jpg" alt="A portrait of Dallin Hooper" class="profile rounded">
        </div>
      </div>
    </div>
    <div class="row mt-3">
      <div class="col-md-6">
        <div class="project-card">

        </div>
      </div>
      <div class="col-md-6">
        <div class="project-card">

        </div>
      </div>
      <div class="col-md-6">
        <div class="project-card">

        </div>
      </div>
      <div class="col-md-6">
        <div class="project-card">

        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
h2 {
  letter-spacing: 0.75rem;
  text-transform: uppercase;
}

.about:hover .profile {
  // opacity: 100;
}

.profile {
  width: 100%;
  object-fit: cover;
  object-position: center;
  // opacity: 0;
  // transition: opacity 0.75s ease-in-out;
}
</style>
