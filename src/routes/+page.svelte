<script lang="ts">
    import { onMount } from 'svelte';
    import { goto } from '$app/navigation';

    onMount(() =>{
        goto('/login');
    })
</script>

<div class="bg-red-200 h-screen">
    <h1>Welcome to MyMind</h1>
    <p>what does mymind do? man i dont even know</p>
    <p>login button on the bottom left, logo on the bottom right</p>
</div>