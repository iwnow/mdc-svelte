<script>
        import {MDCRipple} from '@material/ripple/index';
        import {onMount} from 'svelte';

        let componentRef;
    
        onMount(() => {
            const ripple = Boolean(isRipple) ? new MDCRipple(componentRef) : null;
        });
    
        export let text;
        export let isRipple;
    </script>
        
<button bind:this={componentRef} class="btn mdc-button">
                {text}
              </button>