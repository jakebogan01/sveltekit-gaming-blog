<script>
     import "../styles/app.css";
     import Title from "$lib/title.svelte";
</script>

<header class="flex justify-center py-5 bg-[#2e1e42]">
     <Title title="Ninja Gaming Guides" />
</header>
<main class="max-w-[960px] mt-[20px] mx-auto">
     <slot />
</main>
<footer class="text-center">
     <p>Copyright 2022 Ninja Gaming Guide</p>
</footer>