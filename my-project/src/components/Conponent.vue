<template>
    <div>
        <header>{{title}}</header>
        <div>{{content}}</div>
    </div>
</template>

<script>
export default {
    name: 'component',
    data () {
        return {
            title: 'Components',
            content: 'Creating Component in Vue is easy'
        }
    }
}
</script>