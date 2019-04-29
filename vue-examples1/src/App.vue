<template>
  <div>
    <myheader />
    <div id="main">
      <mysidebar />
      <myarticle />
    </div>
    <myfooter />
  </div>
</template>
<script>
export default {
  components: {
    myheader: () => import("./views/Header"),
    myfooter: () => import("./views/Footer"),
    mysidebar: () => import("./views/Sidebar"),
    myarticle: () => import("./views/Article")
  }
};
</script>

<style>
#main {
  margin: 5px 0px;
  border: 1px solid red;
}
</style>
