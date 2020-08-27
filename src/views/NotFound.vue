<template>
  <div class="NotFound">
    <v-container>
      <v-layout row wrap>
        <v-flex xs12>
          <v-card height="400" color="transparennt" flat>
            <div class="dispaly-3 mt-5">Page Not Found</div>
            <div class="grey--text lighten-5">
              The page you are trying to get never existed in this reality.
              Or has migrated to a parallel universe ;)
            </div>
            <div class="paragraph-text mt-2">
              <br />
              <br />Try going back to home page and repeating your action. Or, contact helpdesk for support
            </div>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.paragraph-text {
  font-size: 18px;
}
</style>