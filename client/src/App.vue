<template>
  <div id="app">
    <UserForm></UserForm>
  </div>
</template>

<script>
import UserForm from "@/components/UserForm";
export default {
  name: "app",
  components: {
    UserForm
  },
  data() {
    return {};
  }
};
</script>

<style lang="scss">
@import "./scss/_variables.scss";
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;

  #app {
    font-family: "Avenir", Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;

    h1 {
      color: $color-primary-dark;
      padding: 10px 15px;
    }
  }
}
</style>
