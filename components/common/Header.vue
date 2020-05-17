<template>
    <header class="header">
        <nav class="navbar navbar-expand-lg">
            <div class="container">
                <nuxt-link class="navbar-brand" to="/">Movie</nuxt-link>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ml-auto">
                        <nuxt-link class="nav-item" tag="li" to="/" exact>
                            <a class="nav-link" href="#">Home</a>
                        </nuxt-link>
                        <nuxt-link class="nav-item" tag="li" to="/movies/top-rated">
                            <a class="nav-link" href="#">Top Rated</a>
                        </nuxt-link>
                        <nuxt-link class="nav-item" tag="li" to="/movies/now-playing">
                            <a class="nav-link" href="#">Now Playing</a>
                        </nuxt-link>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
</template>

<script>
    export default {
        name: "Header",
    }
</script>

<style scoped>

</style>
