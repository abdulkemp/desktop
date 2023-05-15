<template>
  <div>
    <div
      class="modal fade justify-content-start"
      id="exampleModal"
      tabindex="-1"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h1 class="modal-title fs-5" id="exampleModalLabel">Modal title</h1>
            <button
              type="button"
              class="btn-close"
              data-bs-dismiss="modal"
              aria-label="Close"
            ></button>
          </div>
          <div class="modal-body">
            <iframe src="http://googlerep.netlify.app" frameborder="0" width="900" height="570"></iframe>
          </div>
          <!-- <div class="modal-footer">
            <button
              type="button"
              class="btn btn-secondary"
              data-bs-dismiss="modal"
            >
              Close
            </button>
            <button type="button" class="btn btn-primary">Save changes</button>
          </div> -->
        </div>
      </div>
    </div>
    <Folders />
  </div>
</template>

<script>
import Folders from "../components/Folders.vue";
export default {
  name: "Home",
  components: {
    Folders,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.modal-content{
  width: fit-content;
  height: 42rem;
}

/* .modal{
  position: absolute;
} */
</style>