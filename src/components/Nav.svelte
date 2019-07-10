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
		content: '';
		display: block;
		clear: both;
	}

	li {
		display: block;
		float: left;
	}

	.selected {
		position: relative;
		display: inline-block;
	}

	.selected::after {
		position: absolute;
		content: '';
		width: calc(100% - 1em);
		height: 4px;
		background-color: rgb(248, 80, 61);
		display: block;
		bottom: -2px;
	}

	a {
		text-decoration: none;
		padding: 1em 0.5em;
		display: block;
	}
</style>

<nav>
	<ul>
		<li><a class='{segment === undefined ? "selected" : ""}' href='.'>home</a></li>
		<li><a class='{segment === "projects" ? "selected" : ""}' href='projects'>projects</a></li>
		<li><a class='{segment === "internships" ? "selected" : ""}' href='internships'>internships</a></li>
		<li><a class='{segment === "resume" ? "selected" : ""}' href='resume'>resume</a></li>
		<li><a class='{segment === "linkedin" ? "selected" : ""}' href='linkedin'>linkedin</a></li>
		<li><a class='{segment === "contactme" ? "selected" : ""}' href='contactme'>contact</a></li>
	</ul>
</nav>