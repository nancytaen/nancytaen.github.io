<template>
  <div>
    <section class="mt-4 mb-4">
      <b-card overlay class="mt-5" img-src="img/header.jpg"
       title="Hello! I'm Nancy Li">
       <em>A Backend & Full Stack Engineer interested in software engineering and system design </em>
      </b-card>
    </section>

    <section id ="about" class="mt-3 mb-4">
      <h1 class="pt-5">About Me</h1>
      <About />
    </section>

    <section id="skills" class="mt-5 mb-4">
      <h1 class="pt-5">Skills</h1>
      <Skills />
    </section>

    <section id="experience" class="mt-5 mb-5">
      <h1 class="pt-5">Experience</h1>
      <Experience />
    </section>

    <section id ="projects" class="mt-4 mb-5">
      <h1 class="pt-5">Projects</h1>
      <Projects />
    </section>

    <section id ="contact" class="mt-4 mb-4">
      <h1 class="pt-5">Contact</h1>
      <Contact />  
    </section>
  </div>
</template>

<script>
import About from './About.vue'
import Skills from './Skills.vue'
import Experience from './Experience.vue'
import Projects from './Projects.vue'
import Contact from './Contact.vue'

export default {
  name: 'Layout',
  props: {
    msg: String
  },
  components: { About, Skills, Experience, Projects, Contact }
}
</script>
