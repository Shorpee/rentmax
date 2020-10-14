<template>
  <nav>
    
      <section class="navbar shadow-sm navbar-dark bg-dark ">
        <form class="form-inline position-relative mx-auto">
          <i
            class="fa fa-search position-absolute fa-lg"
            aria-hidden="true"
          ></i>
          <input class="form-control rounded-pill" type="text" placeholder="Search" />
        </form>
        <div class="d-flex align-items-center">
          <i class="fa fa-envelope fa-lg mr-3"
            ><span class="dot sec counter counter-lg"></span
          ></i>
          <i class="fa fa-bell fa-lg" aria-hidden="true"></i>
          <div class="d-flex flex-row align-items-center">
              <i class="fa fa-user-circle mr-2" aria-hidden="true"></i>
            <!-- <i class="fa fa-user-circle-o fa-3x mr-2" aria-hidden="true"></i> -->
            <span class="d-block mr-3">
              <h5 class="username my-0">Wisdom Ifenkwe</h5>
              <p class="my-0">Landlord</p>
            </span>
            <i class="fa fa-angle-down fa-lg" aria-hidden="true"></i>
          </div>
        </div>
      </section>
    
      <section class="navbar shadow-sm navbar-expand-lg navbar-light bg-light d-flex align-items-center justify-content-between">
       
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#"><i class="fa fa-th-large" aria-hidden="true"></i>Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><i class="fa fa-building" aria-hidden="true"></i>My Properties</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><i class="fa fa-home" aria-hidden="true"></i>My Rentals</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><i class="fa fa-wallet"></i>Wallet</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><i class="fa fa-credit-card" aria-hidden="true"></i>Cards</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><i class="fa fa-users" aria-hidden="true"></i>Commissions</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><i class="fa fa-user" aria-hidden="true"></i>Profile</a>
            </li>
          </ul>
          <button class="rounded-pill shadow py-2 px-5"><i class="fa fa-plus" aria-hidden="true"></i>New Property</button>
      </section>

  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>


<style scoped>
.navbar-dark {
  background-color: #171523 !important;
}

.navbar-dark input {
  width: 23em !important;
  font-weight: 500;
  padding-left: 40px;
  outline: none;
}

.form-control {
  font-family: "Montserrat", sans-serif;
  font-size: small;
  padding-left: 40px;
  width: 400px;
}

.navbar-light {
    padding-right: auto;
    padding-left: auto;
    padding-top: 20px;
    padding-bottom: 10px;
}

.nav-item {
    font-weight: 500;
    margin-right: 10px;
    position: relative;
}

.nav-item:hover::after {
    content: "";
    display: block;
    margin: 0 auto;
    position: absolute;
    width: 100%;
    bottom: -10px;
    height: 3px;
    background: #14A24D;
}

.nav-item:hover i{
  color:#14A24D;
}




.nav-link > .fa {
  color: #CFCFCF;
  margin-right: 10px;
}

.fa-user-circle {
    font-size: 40px;
}


.fa {
  color: #ffffff;
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
  background-color: #14A24D;
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

button {
  background: #0F7638;
  font-family: "Montserrat", sans-serif;
  font-weight: 500;
  color: #ffffff;
  outline: none;
  border: none;
}

.fa-plus {
  margin-right: 20px;
}
</style>