<template>
    <Head title="Index" />

    <div class="m-5">
        <Link class="text-blue-500 hover:underline hover:text-blue-300" href="/about">About</Link>
        <div class="mt-2 p-5 bg-red-400 rounded-md">
            <h1 class="text-5xl font-black text-white">Hello World</h1>
            <span class="mt-2 block text-red-200">Welcome to lavuta + i</span>
        </div>
    </div>
</template>

<script>
import { Link, Head } from "@inertiajs/inertia-vue3";

export default {
    components: {
        Link,
        Head,
    },
};
</script>