<template>
  <section class="container">
    <div class="columns">
      <div class="column">
        <h1 class="title has-text-centered">Seminario 2</h1>

        <p>Reinforcement learning es una parte de Machine Learning en la que
          un agente aprende a desenvolverse en un ambiente realizando acciones
          que maximicen una recompensa. 
        </p>

        <h3 class="subtitle"> Este trabajo consta de las siguientes partes</h3>
        <ul>
          <li> La idea principal del Aprendizaje por Reforzamiento</li>
          <li> Los tres enfoques del Aprendizaje por reforzamiento</li>
        </ul>
        
        <figure class="image container">
          <img src="https://cdn-images-1.medium.com/max/1600/1*aKYFRoEmmKkybqJOvLt2JQ.png" alt="">
          Fuente : <a href="https://medium.freecodecamp.org/an-introduction-to-reinforcement-learning-4339519de419">
                    Introducción al aprendizaje por reforzamiento
                    </a>
        </figure>

        <section class="hero is-medium is-bold">
          <div class="hero-body">
            <div class="container">
              <h1 class="title">
                Formas de aprendizaje
              </h1>
              <h2 class="subtitle">
                Monte Carlo y Temporal Difference Learning
              </h2>
            </div>
          </div>
        </section>        

        <h3 class="subtitle">Fuentes papers</h3>
        
        <h4>Deep mind, arquitectura deep q learning</h4>
        <a href="https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf">
          https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf
        </a>

        <h4>Open AI Gym</h4>
        <a href="https://arxiv.org/pdf/1606.01540.pdf">
          https://arxiv.org/pdf/1606.01540.pdf
        </a>

        <h4>Open AI Gym MDP</h4>
        <a href="https://arxiv.org/pdf/1709.09069.pdf">
          https://arxiv.org/pdf/1709.09069.pdf
        </a>

        <h3 class="subtitle">Fuentes Web</h3>
        <h4>Ecuaciones de bellman</h4>
        <a href="https://joshgreaves.com/reinforcement-learning/understanding-rl-the-bellman-equations/">
          https://joshgreaves.com/reinforcement-learning/understanding-rl-the-bellman-equations/
        </a>

        <h4>Open AI Gym</h4>
        <a href="https://arxiv.org/pdf/1606.01540.pdf">
          https://arxiv.org/pdf/1606.01540.pdf
        </a>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>

</style>
