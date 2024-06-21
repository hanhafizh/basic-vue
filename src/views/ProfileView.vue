<template>
  <div class="profile">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <div class="media text-left">
            <img src="../assets/farhan-poto.png" class="user-pic mr-3" />
            <div class="media-body">
              <h5 class="mt-0">Farhan Hafizh</h5>
              <p>
                Cras sit amet nibh libero, in gravida nulla. Nulla vel metus
                scelerisque ante sollicitudin
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "ProfileView",
  components: {},
};
</script>

<style scoped>
.user-pic {
  border-radius: 200%;
  height: 90px;
  width: 90px;
}
</style>
