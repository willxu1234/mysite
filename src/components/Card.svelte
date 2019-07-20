<script>
    import { fly } from 'svelte/transition';

    export let duration;
</script>

<style>
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        color: rgb(0, 204, 255);
        border-top: 3px rgb(0, 204, 255) solid;
    }

</style>

<div in:fly="{{x: 200, duration: duration}}" class="wrapper">
    <slot id="left" class="col-5" name="left"></slot>
    <slot id="right" class="col-5" name="right"></slot>
</div>