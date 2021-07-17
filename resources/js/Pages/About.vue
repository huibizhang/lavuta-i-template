<template>
    <Head title="About" />

    <div class="m-5">
        <Link class="text-blue-500 hover:underline hover:text-blue-300" href="/">Back to Home</Link>
        <div class="mt-2 p-5 bg-green-400 rounded-md">
            <h1 class="text-5xl font-black text-white">About</h1>
            <span class="mt-2 block text-green-200">This project are using :</span>
            <ul class=" text-green-100 mt-2">
                FrontEnd
                <ul class="list-disc text-white ml-4 mb-2">
                    <li>Vue 3</li>
                    <li>TailwindCSS 2.2</li>
                    <li>Inertia.js</li>
                </ul>
                BackEnd
                <ul  class="list-disc text-white ml-4 mb-2">
                    <li>Laravel 8</li>
                    <li>Inertia for Laravel</li>
                </ul>
            </ul>
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
