<template>
  <header>
    <div class="container">
        <div class="row">
            <div class="col">
                <h1>BoolBlog</h1>
            </div>
            <div class="col">
              <nav>
                <ul>
                  <li><router-link :to="{ name: 'home' }">Home</router-link></li>
                  <li><router-link :to="{ name: 'about' }">Chi siamo</router-link></li>
                  <li><a href="/admin/home">Area Privata</a></li>
                </ul>
              </nav>
            </div>
        </div>
    </div>
  </header>
</template>

<script>
export default {
    name: 'BaseHeader',
}
</script>

<style>

</style>