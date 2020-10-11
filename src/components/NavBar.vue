<template>
  <nav class="navbar navbar-dark bg-dark py-3">
    <form class="form-inline position-relative mx-auto">
      <i class="fa fa-search position-absolute fa-lg" aria-hidden="true"></i>
      <input class="form-control" type="text" placeholder="Search" />
    </form>
    <div class="d-flex align-items-center">
      <i class="fa fa-envelope fa-lg mr-3"
        ><span class="dot sec counter counter-lg"></span
      ></i>
      <i class="fa fa-bell fa-lg" aria-hidden="true"></i>
      <div class="d-flex flex-row align-items-center">
        <i class="fa fa-user-circle-o fa-3x mr-2" aria-hidden="true"></i>
        <span class="d-block mr-3">
          <h5 class="username my-0">Wisdom Ifenkwe</h5>
          <p class="my-0">Landlord</p>
        </span>
        <i class="fa fa-angle-down fa-lg" aria-hidden="true"></i>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>


<style scoped>
.navbar {
  background-color: #171523 !important;
}

.form-control {
  font-family: "Montserrat", sans-serif;
  font-size: small;
  padding-left: 40px;
  width: 400px;
}

.navbar input {
  width: 23em !important;
  border-radius: 20px;
  font-weight: 500;
}

.fa {
  color: #fff;
  /* font-size: 20px; */
}

.fa-search {
  color: #b5b6b7;
  left: 3%;
}

.fa-bell {
  margin-right: 40px;
}

.dot {
  height: 10px;
  width: 10px;
  background-color: rgb(0, 207, 0);
  border-radius: 50%;
  display: inline-block;
}

.sec {
  position: relative;
  right: 5px;
  top: 0px;
}

.counter.counter-lg {
  top: -8px !important;
}

.username {
  font-weight: 600;
  font-size: 16px;
  color: #ffffff;
}

p {
  font-weight: 500;
  font-size: 14px;
  color: #ffffff;
}
</style>