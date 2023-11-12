<template>
    <div class="task-content">
        <span class="task-label">{{label}}</span>
        <div class="task-description">
          <h3>{{description}}</h3>
        </div>
        <p class="task-priority">Prioriteit: {{priority}}</p>
      </div>
</template>

<script>
export default {
    props: [
        'label',
        'description',
        'priority'
    ]
}
</script>
<style>
    
</style>