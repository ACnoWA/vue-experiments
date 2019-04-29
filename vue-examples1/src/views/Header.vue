<template>
  <div>
    <ul>
      <li>
        <a class="active" href="#">Home</a>
      </li>
      <li>
        <a href="#">News</a>
      </li>
      <li>
        <a href="#">Contact</a>
      </li>
      <li>
        <a href="#">About</a>
      </li>
      <li class="right">
        <a href="#">Logout</a>
      </li>
    </ul>
  </div>
</template>
<style scoped>
div {
  padding: 5px;
  border: 1px solid red;
  margin: 5px 10px;
}
ul {
  display: flex;
  list-style-type: none;
  margin: 0;
  padding: 0;
  background-color: #333;
}
a {
  display: block; /* 变为block级，填充高宽 */
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
.active {
  background-color: #4caf50;
}
a:hover {
  background-color: #111;
}
.right {
  margin-left: auto;
}
</style>
