<script>
    import "../app.css";
    import Header from "../components/Header.svelte";
</script>

<div class="container">
    <div class="columns">
        <div class="column col-6 col-mx-auto main--container">
            <Header />
            <slot />
        </div>
    </div>
</div>

<style>
    .main--container {
        padding-top: 32px;
    }
</style>
