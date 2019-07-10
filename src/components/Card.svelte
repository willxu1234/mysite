<script>
    export let backgroundColor;
    export let color;
</script>

<style>
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
    }

</style>

<div class="wrapper" style="background-color: {backgroundColor}; color: {color}; border-top: 5px {color} solid;">
    <slot id="left" class="col-5" name="left"></slot>
    <slot id="right" class="col-5" name="right"></slot>
</div>