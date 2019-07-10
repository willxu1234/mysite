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
    /* font-size: 7em; */
    font-size: 9vw;
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
    font-size: 3vw;
    padding: 1em 0.4em;
    border: 0.5em black solid;
  }

  .primary {
    color: white;
  }

  .alt {
    color: black;
  }

  div.block {
    background-color: black;
    content: '';
    height: 0.6em;
    width: 100%;
  }
</style>

<svelte:head>
  <title>Will Xu</title>
</svelte:head>

<div class="col-12 hero">
  <h1 class="col-5 display">
    <strong>will xu:</strong>
    <div class="block"></div>
  </h1>
  <div class="col-5 display-sub">
    <h4 class="primary">UCSD 4th Year, <strong>Computer Science;</strong></h4>
    <h4 class="alt">Interested in Software Development;</h4>
    <h4 class="primary">Likes <strong>Autonomous</strong> Vehicles;</h4>
    <h4 class="alt">& Likes <strong>Helping People</strong> Through Code.</h4>
  </div>
</div>
