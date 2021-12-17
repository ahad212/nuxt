<template>
    <div class="about">
        {{msg}}
        <header>
            <ul>
                <li><NuxtLink to="/about/sub">home</NuxtLink></li>
                <li><NuxtLink to="/about/sub2">home</NuxtLink></li>
            </ul>
        </header>
        <section>
            <Nuxt/>
        </section>
        <footer></footer>
    </div>
</template>

<script>
export default{
    data() {
        return{
            msg:"About page"
        }    
    }
}
</script>
