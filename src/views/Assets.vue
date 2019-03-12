<template>
  <div class="wrapper flex-row">
    <assetsNavigation />
    <div class="main-content">
      <h1 class="project" style="margin: 1.5rem 0;">Wilson Language Training Assets</h1>

      <h2 class="project" id="wilsonlogo">Wilson Logo</h2>
      <h4 class="project" id="logovariations">Logo Variations</h4>
      <div class="display-container image-container">
        <!-- <a download="custom-filename.jpg" href="/path/to/image" title="ImageName">
          <img alt="ImageName" src="/path/to/image">
        </a> -->
        <div>
          <img alt="img" src="/path/top/image">
          <span>good</span>
          <div class="row">
            <button class="primary sm">svg</button>
            <button class="primary sm">png</button>
            <button class="primary sm">small png</button>
          </div>
        </div>

        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <div class="row">
            <button class="primary sm">svg</button>
            <button class="primary sm">png</button>
            <button class="primary sm">small png</button>
          </div>
        </div>

        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <div class="row">
            <button class="primary sm">svg</button>
            <button class="primary sm">png</button>
            <button class="primary sm">small png</button>
          </div>
        </div>

        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <div class="row">
            <button class="primary sm">svg</button>
            <button class="primary sm">png</button>
            <button class="primary sm">small png</button>
          </div>
        </div>

        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <div class="row">
            <button class="primary sm">svg</button>
            <button class="primary sm">png</button>
            <button class="primary sm">small png</button>
          </div>
        </div>

        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <div class="row">
            <button class="primary sm">svg</button>
            <button class="primary sm">png</button>
            <button class="primary sm">small png</button>
          </div>
        </div>

      </div>

      <h4 class="project" id="whatnottodowithlogo">What not to do with the Wilson logo</h4>
      <div class="display-container image-container">
        <div>
          <img alt="img" src="../assets/project/wrong/wlt-logo-wrong-01.png">
          <span>Vertical Squish</span>
        </div>

        <div>
          <img alt="img" src="../assets/project/wrong/wlt-logo-wrong-02.png">
          <span>Horizontal Squish</span>
        </div>

        <div>
          <img alt="img" src="../assets/project/wrong/wlt-logo-wrong-03.png">
          <span>Tilt</span>
        </div>

        <div>
          <img alt="img" src="../assets/project/wrong/wlt-logo-wrong-04.png">
          <span>Invert Colors</span>
        </div>

        <div>
          <img alt="img" src="../assets/project/wrong/wlt-logo-wrong-05.png">
          <span>Gradients</span>
        </div>

        <div>
          <img alt="img" src="../assets/project/wrong/wlt-logo-wrong-06.png">
          <span>Swap Colors</span>
        </div>
      </div>

      <h2 class="project" id="programlogos">Program Logos</h2>
      <h4 class="project" id="fundationslogos">Fundations Logos</h4>
      <div class="display-container image-container">
        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <button class="primary sm">Download</button>
        </div>

        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <button class="primary sm">Download</button>
        </div>

        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <button class="primary sm">Download</button>
        </div>
      </div>

      <h4 class="project" id="justwordslogos">Just Words Logos</h4>
      <div class="display-container image-container">
        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <button class="primary sm">Download</button>
        </div>

        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <button class="primary sm">Download</button>
        </div>

        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <button class="primary sm">Download</button>
        </div>
      </div>

      <h4 class="project" id="wrslogos">WRS Logos</h4>
      <div class="display-container image-container">
        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <button class="primary sm">Download</button>
        </div>

        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <button class="primary sm">Download</button>
        </div>

        <div>
          <img alt="img" src="/path/to/image">
          <span>good</span>
          <button class="primary sm">Download</button>
        </div>
      </div>

      <h2 class="project" id="icons">Icons</h2>
      <h4 class="project" id="basiciconset">Basic Icon Set</h4>
      <div class="display-container image-container">

      </div>

      <h4 class="project" id="extendediconset">Extended Icon Set</h4>
      <div class="display-container">

      </div>

    </div>

  </div>
</template>

<script>
import assetsNavigation from '@/components/assetsNavigation.vue'

export default {
  name: 'assets',
  components: {
    assetsNavigation
  }
}
</script>

<style lang="scss">
// Move to Project Stylesheet
.image-container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  > * {
    margin: 1rem 2rem;
    display: flex;
    flex-direction: column;
    justify-items: center;
    font-size: 1rem;
    font-weight: 600;
    text-align: center;
    color: black;
  }
}
img {
  height: 10rem;
}
</style>
