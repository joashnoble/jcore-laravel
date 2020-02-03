<template>
    <div>
      <b-card-group>
        <b-card title="Title" header-tag="header" footer-tag="footer">
          <template v-slot:header>
            <h6 class="mb-0">Category List</h6>
          </template>
          <!-- <b-card-text>Header and footers using slots.</b-card-text> -->
          <!-- <b-button href="#" variant="primary">Go somewhere</b-button> -->
          <!-- <template v-slot:footer>
            <em>Footer Slot</em>
          </template> -->


          <div>
            <b-table striped hover :items="items"></b-table>
          </div>

        </b-card>
      </b-card-group>
    </div>
</template>

<script>
export default {
  name: 'category'
}
</script>