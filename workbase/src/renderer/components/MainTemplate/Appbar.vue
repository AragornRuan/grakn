<template>
<div>
    <nav role="navigation" class="navbar-fixed noselect">
        <div class="nav-wrapper">
            <span>GRAKN Workbase</span>
        </div>
    </nav>
</div>
</template>

<style scoped>

.nav-wrapper {
    display: flex;
    padding-top: 5px;
    justify-content: center;
}

.navbar-fixed {
    position: relative;
    z-index: 10;
    min-height: 25px;

    /* Make navbar draggable area in app.*/
    -webkit-app-region:drag;
    border-bottom: 1px solid #232323;
}

.dark .navbar-fixed{
    background-color:#282828;
}

.light .navbar-fixed{
    background-color:lightblue;
}

</style>

<script>

export default {

  data() {
    return {

    };
  },
  created() {},
  mounted() {
    this.$nextTick(() => {
    });
  },
  methods: {

  },
};
</script>
