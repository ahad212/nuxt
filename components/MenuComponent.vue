<template>
    <div class="menu">
        <div class="menu">
            <ul>
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/about">About</NuxtLink></li>
                <li><NuxtLink to="/">vue</NuxtLink></li>
                <li><NuxtLink to="/">ajax</NuxtLink></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default{
    data() {
        return {
            msg:'menu'
        }
    }
}
</script>
