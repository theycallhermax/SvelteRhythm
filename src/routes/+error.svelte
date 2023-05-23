<script>
    import { page } from '$app/stores';
</script>

<div class="m-3">
    <div class="p-5 mb-3 bg-violet-400 rounded max-h-screen">
        <p class="text-xl font-bold">{$page.error.message}</p>
    </div>
</div>