<template>
	<nav class="main-nav">
		<router-link :to="{ name: 'Home' }">Projects</router-link>
		<router-link :to="{ name: 'AddProject' }">Add a New Project</router-link>
	</nav>
</template>

<script>
export default {};
</script>

<style>
.main-nav {
	text-align: center;
	margin: 25px auto 40px;
}

.main-nav a {
	display: inline-block;
	text-decoration: none;
	margin: 0 18px;
	color: #999;
	font-size: 18px;
	font-weight: 500;
}

.main-nav a:hover {
	color: #555;
}

a.router-link-active {
	border-bottom: 2px solid #00ce89;
	padding-bottom: 4px;
}
</style>
