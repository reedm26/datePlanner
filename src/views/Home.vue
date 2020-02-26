<template>
  <div class="home container-fluid bg">
    <div class="row">
      <div class="col-12">
        <h1 class="title-font">Lets Plan That Date</h1>
      </div>
    </div>
    <div>
      <form>
        <div class="form-row">
          <div class="col-3">
            <label class="mr-sm-2" for="inlineFormCustomSelect">Time During Day?</label>
            <select class="custom-select mr-sm-2" id="inlineFormCustomSelect">
              <option selected>Time Frame...</option>
              <option value="1">Morning</option>
              <option value="2">Afternoon</option>
              <option value="3">Evening</option>
            </select>
          </div>
          <div class="col-3">
            <label class="mr-sm-2" for="inlineFormCustomSelect">Budget?</label>
            <select class="custom-select mr-sm-2" id="inlineFormCustomSelect">
              <option selected>Budget...</option>
              <option value="1">$1-$25</option>
              <option value="2">$26-$50</option>
              <option value="3">$51-$75</option>
              <option value="3">$76-$100</option>
              <option value="3">$100+</option>
            </select>
          </div>
          <div class="col-3">
            <label class="mr-sm-2" for="inlineFormCustomSelect">Time During Day?</label>
            <select class="custom-select mr-sm-2" id="inlineFormCustomSelect">
              <option selected>Choose...</option>
              <option value="1">Morning</option>
              <option value="2">Afternoon</option>
              <option value="3">Night</option>
            </select>
          </div>
          <div class="col-3">
            <label class="mr-sm-2" for="inlineFormCustomSelect">Time During Day?</label>
            <select class="custom-select mr-sm-2" id="inlineFormCustomSelect">
              <option selected>Choose...</option>
              <option value="1">Morning</option>
              <option value="2">Afternoon</option>
              <option value="3">Night</option>
            </select>
          </div>
        </div>
      </form>
      <div>results:</div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
<style>
.bg {
  background: linear-gradient(rgba(61, 61, 61, 0.5), rgba(88, 88, 88, 0.5)),
    url(https://www.elsetge.cat/myimg/f/14-144139_cloud-desktop-background-hd.jpg);
  /* background-size: auto; */
  height: 1000px;
  width: auto;
  background-repeat: no-repeat;
  background-position: 0px, 0px, 0px, 0px;
  opacity: 99;
}
.title-font {
  font-family: Trebuchet, Helvetica;
}
</style>
d