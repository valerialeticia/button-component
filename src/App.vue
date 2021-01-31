<template>
  <v-app>
    <v-container>
      <v-main>
        <h2>Inputs</h2>

        <v-row class="my-5">
          <v-col cols="12" lg="3" md="3">
            <Input label="Label" :outlined="true" />
          </v-col>
        </v-row>

        <v-row class="my-5">
          <v-col cols="12" lg="3" md="3">
            <Input label="Label" :outlined="true" :error="true" />
          </v-col>
        </v-row>

        <v-row class="my-5">
          <v-col cols="12" lg="3" md="3">
            <Input label="Label" :outlined="true" :disabled="true" />
          </v-col>
        </v-row>

      <v-row class="my-5">
         <v-col cols="12" lg="3" md="3">
            <Input label="Label" :outlined="true" messages="Some interesting text" />
        </v-col>
        <v-col cols="12" lg="3" md="3">
          <Input label="Label" :outlined="true" :error="true" messages="Some interesting text" />
        </v-col>
      </v-row>

      <v-row class="my-5">
        <v-col cols="12" lg="3" md="3">
          <Input label="Label" :outlined="true" prependInnerIcon="mdi-phone" />
        </v-col>
        <v-col cols="12" lg="3" md="3">
          <Input label="Label" :outlined="true" appendIcon="mdi-lock" />
        </v-col>
      </v-row>

      <v-row class="my-5">
        <v-col cols="12" lg="3" md="3">
          <Input message="Text" label="Label" :outlined="true" />
        </v-col>
      </v-row>

      <v-row class="my-5">
        <v-col cols="12" lg="3" md="3">
          <Input message="Text" label="Label" :outlined="true" :dense="true" />
        </v-col>
        <v-col cols="12" lg="3" md="3">
          <Input label="Label" :outlined="true" />
        </v-col>
      </v-row>

      <v-row class="my-5">
        <v-col cols="12">
          <Input message="Text" label="Label" :outlined="true" />
        </v-col>
      </v-row>

      <v-row class="my-5">
        <v-col cols="12" lg="3" md="3">
          <v-textarea rows="4" label="Label" outlined />
        </v-col>
      </v-row>

      <span class="grey--text">Valéria Letícia @ DevChallenges.io</span>
      </v-main>
    </v-container>
  </v-app>
</template>

<script>
import Input from './components/Input'
export default {
  name: 'Inputs',

  components: {
    Input
  }
}
</script>
