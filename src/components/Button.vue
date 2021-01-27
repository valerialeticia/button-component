<template>
    <div>
        <v-btn 
            :outlined="outlined" 
            :disabled="disabled" 
            :text="text"
            :color="color"
            :elevation="elevation"
            :dark="dark"
            :small="small"
            :x-large="large"
            class="text-capitalize rounded-lg">
            <v-icon class="mr-2">{{ iconLeft }}</v-icon>
            {{ label }}
            <v-icon class="ml-2">{{ iconRight }}</v-icon>
        </v-btn>
    </div>
</template>

<script>
export default {
    props: {
        label: {
            type: String,
            default: ''
        },
        iconRight: {
            type: String,
            default: ''
        },
        iconLeft: {
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
        text: {
           type: Boolean,
            default: false 
        },
        color: {
            type: String,
            default: ''
        },
        elevation: {
            type: String,
            default: '' 
        },
        dark: {
            type: Boolean,
            default: false
        },
        small: {
            type: Boolean,
            default: false 
        },
        large: {
            type: Boolean,
            default: false 
        }
    }
}
</script>