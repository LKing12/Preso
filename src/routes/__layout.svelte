<script>
    import Notifications from 'svelte-notifications';
    import Deck from '../lib/Deck.svelte';
    import { onMount } from 'svelte';
//     onMount(async () => {
        
//         if ('serviceWorker' in navigator) {
//   navigator.serviceWorker.register('/service-worker.js', { scope: '/' }).then(function(reg) {
//     // registration worked
//     console.log('Registration succeeded. Scope is ' + reg.scope);
//   }).catch(function(error) {
//     // registration failed
//     console.log('Registration failed with ' + error);
//   });
// }; 



//     }); 
</script>

<Notifications>
    <Deck>
        <slot />
    </Deck>
</Notifications>
