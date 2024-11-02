<script>
    import Header from './Header.svelte';
    import Footer from './Footer.svelte';
</script>

<Header />
<main class="container">
    <video 
        src="video/title.mp4" 
        autoplay 
        loop
        muted>
    </video>
</main>
<Footer />

<style>
    video {
        width: 100%;
        aspect-ratio: 2.35/1;
        object-fit: cover;
        object-position: center;
    }
</style>