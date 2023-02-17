<template>
    <div class="container mt-5">
      <div class="col-12 d-flex bg-white pt-4 pb-4" style="border-radius: 5px;">
        <div class="col-2">
          <div class="d-flex justify-content-center align-content-center align-items-center h-100">
            <div>
              <img src="@/assets/images/stfil-logo.svg" style="width: 40px;height: 40px" alt="">
            </div>
            <div class="ml-3">
              <span class="fs-18 fw-extra-bold">stFil</span>
            </div>
          </div>
        </div>
        <div style="height: 55px; width: 1px;background-color: #e2e2e2;">&nbsp;</div>
        <div class="col-10">
          <div class="d-flex">
            <div class="col-3">
              <div class="text-center">
                <div class="fw-medium">Reserve Size</div>
                <div class="fw-extra-bold fs-20">$11.09M</div>
              </div>
            </div>
            <div class="col-3">
              <div class="text-center">
                <div class="fw-medium">Available liquidity</div>
                <div class="fw-extra-bold fs-20">$3.06M</div>
              </div>
            </div>
            <div class="col-3">
              <div class="text-center">
                <div class="fw-medium">Utilization Rate</div>
                <div class="fw-extra-bold fs-20">72.42%</div>
              </div>
            </div>
            <div class="col-3">
              <div class="text-center">
                <div class="fw-medium">Oracle price</div>
                <div class="fw-extra-bold fs-20">$1.00</div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="col-12 bg-white mt-4 p-3" style="border-radius: 5px;">
        <div class="fs-18">
          Reserve status & configuration
        </div>

        <div>
          Supply Info
        </div>
        <div>

        </div>
      </div>

    </div>
</template>

<script>
export default {
  name: 'HomeView',
  components: {
  }
}
</script>
