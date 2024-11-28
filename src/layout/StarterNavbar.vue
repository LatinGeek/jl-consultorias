<!-- eslint-disable vue/no-unused-vars -->
<template>
  <navbar position="fixed" type="primary" menu-classes="ml-auto">
    <template slot-scope="{ toggle, isToggled }">
      <router-link v-popover:popover1 class="navbar-brand" to="/presentation">
        <img src="img\logo-jl.png" style="width: 50px;">
      </router-link>

    </template>
    <template slot="navbar-menu">
      <drop-down tag="li" title="Opciones">
        <nav-link class="dropdown-item">
          <i class="now-ui-icons shopping_box"></i> <a  href="https://www.linkedin.com/in/julio-lamela-94743647/">LinkedIn</a>
        </nav-link>
      </drop-down>
    </template>
  </navbar>
</template>

<script>
import { DropDown, NavbarToggleButton, Navbar, NavLink } from '@/components';
import { Popover } from 'element-ui';

export default {
  name: 'main-navbar',
  components: {
    DropDown,
    Navbar,
    //NavbarToggleButton,
    NavLink,
    [Popover.name]: Popover
  }
};
</script>

<style scoped></style>
