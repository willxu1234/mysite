<script>
  import { fade, fly } from 'svelte/transition';
  import { onMount } from 'svelte';

  let visible = false;

  onMount(() => visible = true);
</script>

<style>
  div.hero {
    height: 80vh;
    display: flex;
    align-items: center;
    align-content: center;
    flex-flow: row wrap;
  }

  h1.display {
    text-align: right;
    margin: 0.5em 0.2em;
    font-size: calc(0.2vw + 2.5em);
    /* font-size: 5vw; */
    color: white;
  }

  /* @media only screen and (min-width: 768px) {
    h1.display {
      transform: rotate(-30deg);
    }
  }
   */
  div.display-sub {
    margin: 0 0.2em 0.5em 0.2em;
    font-size: calc(0.2vw + 1.4em);
    padding: 1em 0.4em;
    border: 0.2em rgb(0, 204, 255) solid;
  }

  .primary {
    color: white;
  }

  .alt {
    color: rgb(180, 180, 180);
  }

  div.block {
    background-color: rgb(0, 204, 255);
    content: '';
    height: 0.1em;
    width: 100%;
  }
</style>

<svelte:head>
  <title>Will Xu</title>
</svelte:head>

{#if visible}
  <div class="col-12 hero">
    <h1 in:fade class="col-5 display">
      hi, i'm will xu:
      <div class="block"></div>
    </h1>
    <div in:fly="{{y: -50, duration: 800}}"class="col-5 display-sub">
      <h4 class="primary">UCSD 4th Year, Computer Science;</h4>
      <h4 class="alt">Interested in Software Development;</h4>
      <h4 class="primary">Likes Autonomous Vehicles;</h4>
      <h4 class="alt">& Likes Helping People Through Code.</h4>
    </div>
  </div>
{/if}
