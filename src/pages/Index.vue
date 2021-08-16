<template>
  <div class="flex flex-center">
    <div class="row justify-center full-width q-pa-lg">
      <q-btn
        label="generate board"
        color="grey-9"
        size="lg"
      />
    </div>
    <div class="row q-pa-sm q-col-gutter-xs">
      <div v-for="index in 16" class="col-3" :key="index">
        <q-btn
          :label="index"
          color="grey-7"
          class="full-width q-pa-sm"
          unelevated
        />
      </div>
    </div>
  </div>
</template>

<script>


export default {
  name: 'OneWord'
}
</script>
