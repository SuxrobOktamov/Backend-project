<script setup>
</script>
<template>
    <header>
        <div class="d-flex flex-column flex-md-row align-items-center pb-3 pt-3 mb-4 border-bottom">
        <RouterLink :to="{name:'home'}" class="d-flex align-items-center link-body-emphasis text-decoration-none">
            <div class="animation"></div>
            <span class="fs-4">Sammi</span>
        </RouterLink>
        <nav class="d-inline-flex mt-2 mt-md-0 ms-md-auto">
            <RouterLink class="me-3 py-2 link-body-emphasis text-decoration-none"  :to="{name:'login'}">Login</RouterLink>
            <RouterLink class="py-2 link-body-emphasis text-decoration-none"  :to="{name:'register'}">Register</RouterLink>
        </nav>
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .animation {
        background: url('https://img.freepik.com/free-photo/elevated-view-two-red-yellow-crumpled-papers_23-2147878568.jpg?size=626&ext=jpg&ga=GA1.2.548799497.1690367930&semt=ais');
        width: 32px;
        height: 32px;
        border-radius: 50%;
        background-size: cover;
    };
</style>