<template>
    <div class="a-dark-mode-toggle">
        <input type="checkbox" class="checkbox">
        <div class="knobs"></div>
        <div class="layer"></div>
    </div>
</template>

<script>
export default {
    mounted() {
        const checkbox = this.$el.querySelector('input')
        checkbox.addEventListener('change', (e) => {
            e.target.checked ? document.documentElement.setAttribute('data-theme', 'dark') : document.documentElement.removeAttribute('data-theme');
        })
    }
}
</script>