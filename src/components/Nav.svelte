<script>
  export let segment;
</script>

<style>
  nav {
    background-color: white;
    border-bottom: 10px solid black;
    font-weight: 300;
    padding: 0 1em;
  }

  ul {
    margin: 0;
    padding: 0;
  }

  /* clearfix */
  ul::after {
    content: "";
    display: block;
    clear: both;
  }

  li {
    display: block;
    float: left;
  }

  li:hover {
    color: rgb(248, 80, 61);
  }

  .selected {
    position: relative;
    display: inline-block;
  }

  .selected::after {
    position: absolute;
    content: "";
    width: calc(100% - 1em);
    height: 5px;
    background-color: rgb(248, 80, 61);
    display: block;
    bottom: 4px;
  }

  a {
    text-decoration: none;
    padding: 1em 0.5em;
    display: block;
  }
</style>

<nav>
  <ul>
    <li>
      <a class={segment === undefined ? 'selected' : ''} href=".">home</a>
    </li>
    <li>
      <a class={segment === 'projects' ? 'selected' : ''} href="projects">
        projects
      </a>
    </li>
    <li>
      <a class={segment === 'internships' ? 'selected' : ''} href="internships">
        internships
      </a>
    </li>
    <li>
      <a
        class={segment === 'resume' ? 'selected' : ''}
        href="pdf/resume.pdf"
        target="_blank"
        rel="noopener">
        resume 🔗
      </a>
    </li>
    <li>
      <a
        class={segment === 'linkedin' ? 'selected' : ''}
        href="https://linkedin.com/in/willxu1234"
        target="_blank"
        rel="noopener">
        linkedin 🔗
      </a>
    </li>
    <li>
      <a
        class={segment === 'github' ? 'selected' : ''}
        href="https://github.com/willxu1234"
        target="_blank"
        rel="noopener">
        github 🔗
      </a>
    </li>
  </ul>
</nav>
