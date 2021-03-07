<template>
  <div id="menu">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
    </ul>
  </div>
</template>

<style>
#menu ul {
  list-style: none;
  display: flex;
  justify-content: center;
}
#menu ul li a {
  padding: 0 10px;
}
#menu ul li + li {
  border-left: 1px solid #333;
}
</style>