<template>
    <button>Clean vue "{{ env }}"</button>
</template>

<script>
    import config from './config';

    export default {
        computed: {
            env() {
                return String(config.SOME_ENV_VARIABLE);
            },
        },
    };
</script>
