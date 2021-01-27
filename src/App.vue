<template>
  <v-app>
    <v-container>
      <v-main>
        <h2>Buttons</h2>

        <v-row class="my-5">
          <v-col cols="12" lg="4" md="4">
            <Button label="Default" />
          </v-col>
        </v-row>

        <v-row class="my-5">
          <v-col cols="12" lg="4" md="4">
            <Button label="Default" :outlined="true" color="indigo accent-4" />
          </v-col>
        </v-row>

        <v-row class="my-5">
          <v-col cols="12" lg="4" md="4">
            <Button label="Default" :text="true" color="indigo accent-4" />
          </v-col>
        </v-row>

      <v-row class="my-5">
        <v-col cols="12" lg="4" md="4">
          <Button label="Default" elevation="0" color="indigo accent-4" :dark="true" />
        </v-col>
      </v-row>

      <v-row class="my-5">
        <v-col cols="12" lg="2" md="2">
          <Button label="Default"  :disabled="true" />
        </v-col>
        <v-col cols="12" lg="2" md="2">
          <Button label="Default"  :disabled="true" :text="true" />
        </v-col>
      </v-row>

      <v-row class="my-5">
        <v-col cols="12" lg="2" md="2">
          <Button label="Default" color="indigo accent-4"  iconLeft="mdi-cart-plus" :dark="true" />
        </v-col>
        <v-col cols="12" lg="2" md="2">
          <Button label="Default" color="indigo accent-4"  iconRight="mdi-cart-plus" :dark="true" />
        </v-col>
      </v-row>

      <v-row class="my-5">
        <v-col cols="12" lg="2" md="2">
          <Button label="Default" color="indigo accent-4" :dark="true" :small="true" />
        </v-col>
        <v-col cols="12" lg="2" md="2">
          <Button label="Default" color="indigo accent-4"  :dark="true" />
        </v-col>
        <v-col cols="12" lg="2" md="2">
          <Button label="Default" color="indigo accent-4" :dark="true" :large="true" />
        </v-col>
      </v-row>

      <v-row class="my-5">
        <v-col cols="12" lg="2" md="2">
          <Button label="Default" color="grey"  />
        </v-col>
        <v-col cols="12" lg="2" md="2">
          <Button label="Default" color="indigo accent-4"  :dark="true" />
        </v-col>
        <v-col cols="12" lg="2" md="2">
          <Button label="Secondary" color="blue-grey darken-3" :dark="true" />
        </v-col>
        <v-col cols="12" lg="2" md="2">
          <Button label="Danger" color="red darken-4" :dark="true" />
        </v-col>
      </v-row>
      </v-main>
    </v-container>
  </v-app>
</template>

<script>
import Button from './components/Button'
export default {
  name: 'Buttons',

  components: {
    Button
  }
}
</script>
