<template>
    <div id="playlistManager">
        <h1 class="title">Playlist Manager</h1>
        <section>
            <songlist></songlist>
            <playlist></playlist>
        </section>
    </div>
</template>

<script>
import Playlist from './Playlist';
import Songlist from './Songlist';

export default {
    name: 'PlaylistManager',
    components: { Playlist, Songlist },
    data() {
        return {
            
        }
    },

  



  
}
</script>

<style scoped>
#playlistManager > section {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 1rem;
    padding: 1rem;
}
</style>