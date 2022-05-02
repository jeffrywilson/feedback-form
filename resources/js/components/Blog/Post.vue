<template>
    <div>
        <div class="uk-card uk-card-default uk-card-hover uk-card-body">
            <h3 class="uk-card-title">{{title}} <span class="uk-badge">{{email}}</span></h3>
            <p class="uk-text-meta uk-margin-remove-top">
                <time datetime="2016-04-01T19:00">{{ date }}</time>
            </p>
            <p>{{body}}</p>
        </div>
        
    </div>
</template>

<script>
    export default {
        props: {
            title: {
                type: String,
                default: "NULL"
            },
            email: {
                type: String,
                default: "NULL"
            },
            body: {
                type: String,
                default: "NULL"
            },
            date: {
                type: String,
                default: "NULL"
            }
        }
    }
</script>

<style scoped>

</style>
