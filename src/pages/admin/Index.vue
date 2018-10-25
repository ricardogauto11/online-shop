<template>
  <div>
    <div class="admin-new">
      <div class="container">
        <div class="col-lg-3 col-md-3 col-sm-12 col-xs-12">
          <ul class="admin-menu">
            <li>
              <router-link to="/admin">View Products</router-link>
            </li>
            <li>
              <router-link to="/admin/new">New Product</router-link>
            </li>
          </ul>
        </div> <!-- col-lg-3 col-md-3 col-sm-12 col-xs-12 -->
        <router-view></router-view>
      </div> <!-- container -->
    </div> <!-- admin-new -->
  </div>
</template>
<script>
export default {
  name: 'home',
  data() {
    return {
      msg: 'Welcome to the Admin Page',
    };
  },
};
</script>

