<script>
    export let backgroundColor;

</script>

<style>
    .wrapper {
        max-width: 56em;
        display: flex;
    }
</style>

<div class="wrapper" style="background-color: {backgroundColor};">
    <slot id="left" name="left"></slot>
    <slot id="right" name="right"></slot>
</div>