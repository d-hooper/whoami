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
    <div class="row mt-3 align-items-lg-stretch">
      <div class="col-lg-6">
        <div class="d-flex flex-column justify-content-evenly h-100 bg-light rounded about py-4 py-lg-0">
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
      <div class="col-lg-6">
        <div class="rounded mt-lg-0 mt-3 h-100">
          <img src="@/assets/img/IMG_8314.jpg" alt="A portrait of Dallin Hooper" class="profile rounded">
        </div>
      </div>
    </div>
    <div class="row mb-3">
      <div class="col-md-6">
        <a href="http://projectu.dallinhooper.com" target="_blank" rel="noopener noreferrer">
          <div class="project-card mt-3">
            <img src="https://images.unsplash.com/photo-1658426837321-9e04e1d227ee?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                 class="project-img"
                 alt="a keyboard, mouse, stylus, and bowlof fruit resting on a chalkboard surface with math equations written on it">
            <div>
              <h3>ProjectU</h3>
              <p class="mb-0">
                ProjectU is a calorie tracking application allowing users to query a third-party API (Spoonacular) for
                nutritional info and save meals and items eaten.
              </p>
            </div>
          </div>
        </a>
      </div>
      <div class="col-md-6">
        <a href="http://keepr.dallinhooper.com" target="_blank" rel="noopener noreferrer">
          <div class="project-card mt-3">
            <img src="https://images.unsplash.com/photo-1634224152857-69c415153d4a?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                 class="project-img" alt="a person using a key to open a safety deposit box">
            <div>
              <h3>Keepr</h3>
              <p class="mb-0">
                Keepr is a social platform for posting 'Keeps' or captioned images and grouping desired images in public
                or private vaults. It features logic comparable to Pinterest.
              </p>
            </div>
          </div>
        </a>
      </div>
      <div class="col-md-6">
        <a href="http://tower.dallinhooper.com" target="_blank" rel="noopener noreferrer">
          <div class="project-card mt-3">
            <img src="https://images.unsplash.com/photo-1464207687429-7505649dae38?q=80&w=2073&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                 class="project-img " alt="a group of people sharing a picnic on a hilltop watching the sunset">
            <div>
              <h3>Tower</h3>
              <p class="mb-0">
                Tower is a site for finding and planning events. Logged in users can set a date and capacity for events,
                see who is attending an event, and even cancel events they are hosting.
              </p>
            </div>
          </div>
        </a>
      </div>
      <div class="col-md-6">
        <a href="http://allspice.dallinhooper.com" target="_blank" rel="noopener noreferrer">
          <div class="project-card mt-3">
            <img src="https://images.unsplash.com/photo-1589152144820-692b189e0b34?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                 class="project-img"
                 alt="a recipe book open to a section describing ingredients and steps for making break">
            <div>
              <h3>All-Spice</h3>
              <p class="mb-0">
                All-Spice is a digital recipe book where logged-in users can create their own recipes, as well as view
                and save recipes created by others.
              </p>
            </div>
          </div>
        </a>
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


.project-card {
  width: 100%;
}

.project-img {
  width: 100%;
  height: 45dvh;
  object-fit: cover;
  object-position: center;
}
</style>
