<template>
  <div>
    <b-card header="SITE LIST PLACEHOLDER COMPONENT">
      <!-- using a loading skeleton table until the requirements
          for sites is identified and modeled in the database -->
      <b-skeleton-table
        :rows="5"
        :columns="3"
        :table-props="{ bordered: false, striped: true }"
      >
      </b-skeleton-table>
    </b-card>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.card-body {
  padding: 0px;
}
.table {
  margin: 0px;
}
</style>
