<template>
  <div>
    <b-navbar id="navbarTop" class="fixed-top justify-content-between" toggleable="lg" type="dark">
      <router-link to="./" class="navbar-brand text-white" style="font-size:1.5em">GreenDistrict</router-link>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse
        id="nav-collapse"
        class="mt-5 justify-content-end"
        style="background-color: #7c9465; "
        is-nav
      >
        <b-navbar-nav style="text-align:right">
          <router-link to="./Dechet" class="nav-link text-white" style="font-size:">Déchêts</router-link>
          <router-link to="./" class="nav-link text-white" style="font-size:">Alimentation</router-link>
          <router-link to="./" class="nav-link text-white" style="font-size:">Energies</router-link>
          <router-link to="./Login" class="nav-link text-white" style="color:#eedada">Aides</router-link>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
<script>
import {
  BNavbar,
  BNavbarBrand,
  BNavbarToggle,
  BNavbarNav
} from "bootstrap-vue/esm/components/navbar";
import { BCollapse } from "bootstrap-vue/esm/components/collapse";
import {
  BNavItem,
  BNavItemDropdown,
  BNavForm
} from "bootstrap-vue/esm/components/nav";
import { BDropdownItem } from "bootstrap-vue/esm/components/dropdown";
import { BFormInput } from "bootstrap-vue/esm/components/form-input";
import { BButton } from "bootstrap-vue/esm/components/button";

export default {
  components: {
    BNavbar,
    BNavbarBrand,
    BNavbarToggle,
    BCollapse,
    BNavbarNav,
    BNavItem,
    BNavItemDropdown,
    BDropdownItem,
    BNavForm,
    BFormInput,
    BButton
  }
};
</script>
<style>
#navbarTop {
  background-color: #7c9465;
}
</style>
