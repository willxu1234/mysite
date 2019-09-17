<script>
  export let segment;
</script>

<style>
  nav {
    background-color: rgb(25, 25, 25);
    border-bottom: 1px solid rgb(0, 204, 255);
    font-weight: 300;
    padding: 0 1em;
    color: white;
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
    color: rgb(0, 204, 255);
  }

  .selected {
    position: relative;
    display: inline-block;
  }

  .selected::after {
    position: absolute;
    content: "";
    width: calc(100% - 1em);
    height: 1px;
    background-color: white;
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
        class={segment === 'linkedin' ? 'selected' : ''}
        href="https://linkedin.com/in/willxu1"
        target="_blank"
        rel="noopener">
        linkedin
      </a>
    </li>
    <li>
      <a
        class={segment === 'github' ? 'selected' : ''}
        href="https://github.com/willxu1"
        target="_blank"
        rel="noopener">
        github
      </a>
    </li>
  </ul>
</nav>
