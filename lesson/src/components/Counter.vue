<template>

    <div>

        <h2>Add:{{ count }} </h2>

        <p>

            <button @click="count += 1">Add count</button>

        </p>

    </div>

</template>

<script>

    export default {

        data() {

            return {

                count: 0

            }

        }

    }

</script>