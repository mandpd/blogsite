<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="About Us"
      subtitle="Learn Data Science through Interactive Data Visualization"
      image="/uploads/about-hero.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
          <h3>About Fluidatum</h3>
          <p>
            Many of the concepts and mathematical foundations of Data Science
            can be challenging to understand on first encountering them. A solid
            grasp of the theory is essential to an accurate and effective
            practice of Data Science. This site focuses on providing interactive
            interactive visualizations of the key concepts behind many of the
            statistical models and approaches utilized by today’s Data
            Scientists. We hope you find these visualizations beneficial in
            helping you to understand how the power of Data Science can be
            leveraged.
          </p>
        </div>
      </template>

      <template v-slot:sidebar>
        <h3 class="subtitle is-4">
          Latest Posts
        </h3>
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>
