<template>
  <b-navbar
    toggleable="md"
    type="dark"
    variant="info"
  >
    <b-navbar-toggle target="nav_collapse" />
    <b-navbar-brand href="#">NavBar</b-navbar-brand>
    <b-collapse
      id="nav_collapse"
      is-nav
    >
      <b-navbar-nav>
        <b-nav-item href="#">Link</b-nav-item>
        <b-nav-item
          href="#"
          disabled
        >
          Disabled
        </b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>
