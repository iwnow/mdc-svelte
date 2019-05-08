<script>
    import Button from './Button.svelte';

    export let name;
</script>
    
    <style>
        h1 {
            color: purple;
        }
    </style>
    
<h1>Hello {name}!</h1>
<div>
    <Button text="mdc button" />
</div>

<div>
    <Button text="mdc ripple button" isRipple />
</div>