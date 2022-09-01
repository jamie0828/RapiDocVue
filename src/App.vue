<template>
  <div>
    <!-- For render-style=read you should try to provide height of rapi-doc element as it needs to calculate scroll positions-->
    <rapi-doc
      spec-url="https://petstore.swagger.io/v2/swagger.json"
      render-style="read"
      style="height:100vh; width:100%"
    ></rapi-doc>
  </div>
</template>

<script>
import "rapidoc";
</script>
