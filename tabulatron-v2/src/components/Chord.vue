<template>
    <v-container class="pa-0">
            <v-text-field v-if="index === numberOfStrings + 1" outlined readonly hide-details="" class="centered-input small-text-size rotated ml-0" v-model="chordName"></v-text-field>
            <v-text-field v-else class="centered-input small-text-size rotated ml-0"></v-text-field>
    </v-container>
</template>

<script>
    export default {
        data() {
            return {
                chordName: '',
                tuning: [],
                numberOfStrings: 6
            }
        },
        props: {    
        tabColumn: {
            default: 0
        },
    },
    }
</script>

<style lang="scss" scoped>

</style>