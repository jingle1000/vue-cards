<template>
    <div class="card" :class="{isCurrent : isCurrent}">
        <h3 class="card-title">{{ card.keyWord }}</h3>
    </div>
</template>

<script>
export default {
    props: {
        card: {
            type: Object,
            required: true
        },
        isCurrent: {
            type: Boolean,
            required: true
        }
    }
}
</script>
