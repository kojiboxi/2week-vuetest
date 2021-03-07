<template>
  <div id="app">
    <Menu></Menu>
    <Home></Home>
    <Member></Member>
  </div>
</template>

<script>
import Menu from "./components/Menu";
import Home from "./components/Home";
import Member from "./components/Member";
export default {
  components: {
    Home,
    Member,
    Menu
  }
};
</script>