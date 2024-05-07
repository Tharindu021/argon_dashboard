<template>
  <div class="card-deck">
    <div class="card bg-gradient-default">
      <div class="card-body">
        <div class="mb-2">
          <sup class="text-white">$</sup>
          <span class="h2 text-white">3,300</span>
          <div class="text-light mt-2 text-sm">
            Your current balance
          </div>
          <div>
            <span class="text-success font-weight-600">+ 15%</span>
            <span class="text-light">($250)</span>
          </div>
        </div>
        <button class="btn btn-sm btn-block btn-neutral">
          Add credit
        </button>
      </div>
      <div class="card-body">
        <div class="row">
          <div class="col">
            <small class="text-light">Orders: 60%</small>
            <div class="progress progress-xs my-2">
              <div class="progress-bar bg-success" style="width: 60%"></div>
            </div>
          </div>
          <div class="col">
            <small class="text-light">Sales: 40%</small>
            <div class="progress progress-xs my-2">
              <div class="progress-bar bg-warning" style="width: 40%"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>

<style lang="scss" scoped></style>