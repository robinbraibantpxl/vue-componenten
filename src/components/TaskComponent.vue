<template>
    <div>
        <p>{{label}}</p>
        <p>{{description}}</p>
        <p>{{prio}}</p>
    </div>
</template>

<script>
export default {
    props: [
        'label',
        'description',
        'prio'
    ]
}
</script>
<style>
    
</style>