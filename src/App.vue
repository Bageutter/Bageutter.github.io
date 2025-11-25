<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />
    <h1>Welcome to My First GitHub Page</h1>
    <nav>
      <ul>
        <li><a href="#intro">Intro</a></li>
        <li><a href="#gain">What do I intend to gain?</a></li>
        <li><a href="#topics">What will I cover?</a></li>
        <li><a href="#closing">Closing statements</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <!-- Content will be inserted here -->
    <h1 id="intro">Intro</h1>
    <p>
      This is my first github page! As of the 29/05/2025, I have decided I will begin a not so
      regular blog for the sake of hashing out my ideas/thoughts on specific topics. Right now it
      will be more of a jarbled mess of nonsense, and maybe if I feel bothered enough, I can turn it
      into something cool.
    </p>

    <h2 id="gain">What do intend to gain?</h2>
    <p>
      TBF, no clue :) I will find a proper use for this, and maybe I'll learn something out of this,
      but it's just an open book right now
    </p>

    <h2 id="topics">What will I cover?</h2>
    <p>
      Everything and anything under the sun that I find interesting. As for particular topics?
      Here's a not-so-definite list I would probably fall back to when I run out of ideas:
    </p>
    <ul>
      <li><strong>Literary Analysis</strong></li>
      <li><strong>The Psychology of Communication</strong></li>
      <li><strong>Technical Deployments</strong></li>
      <li><strong>Cybersecurity</strong></li>
      <li><strong>Routing and Networking</strong></li>
      <li><strong>Photography and arts</strong></li>
    </ul>

    <h1 id="closing">Closing statements</h1>
    <p>
      If you are me, this blog is kinda like a message in a bottle. There is no guarantee I will
      remember whatever tf I was on when writing it, nor is there a guarantee that I will stand by
      what I have said in the past. What you should hopefully remember and hold true is that this is
      suppose to mark your growth throughout the years (hopefully), and or watch how this blog dies
      in a few months from creation :( If you are not me, this blog would be nothing more than a
      brief introspective on who I am as a person, and my view of the world. Think nothing more than
      it being a poorly updated story with too many logical fallacies, and an unreliable narrator.
      Actually, scratch that - don't think of this at all because it is all the more embarrasing for
      the both of us
    </p>
  </main>

  <footer>
    <p>&copy; 2025 My First GitHub Page</p>
  </footer>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
