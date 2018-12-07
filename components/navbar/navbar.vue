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
        <b-nav-item href="/">Home</b-nav-item>
        <b-nav-item
          href="/users"
        >
          Users
        </b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>
