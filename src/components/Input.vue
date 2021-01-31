<template>
    <div>
        <v-hover v-slot="{ hover }">
            <v-text-field 
                v-model="message"
                :label="label"
                :placeholder="placeholder"
                :outlined="outlined"
                :disabled="disabled"
                :messages="messages"
                :append-icon="appendIcon"
                :prepend-inner-icon="prependInnerIcon"
                :error="error"
                :dense="dense"
                class="rounded-lg"
                :class="{'black--text': hover}"/>
        </v-hover>
    </div>
</template>

<script>
export default {
    props: { 
        label: {
            type: String,
            default: ''
        },
        placeholder: {
            type: String,
            default: ''
        },
        outlined: {
            type: Boolean,
            default: false
        },
        disabled: {
            type: Boolean,
            default: false
        },
        messages: {
            type: String,
            default: ''
        },
        appendIcon: {
            type: String,
            default: ''
        },
        prependInnerIcon: {
            type: String,
            default: ''
        },
        message: {
            type: String,
            default: ''
        },
        error: {
            type: Boolean,
            default: false
        },
        dense: {
            type: Boolean,
            default: false
        }
    }
}
</script>
