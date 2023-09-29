<template>    
    <header class="header">
            <div class="header__menu center">
                <div class="header__logo">
                    <a href="index.html">
                        <svg width="34" height="34" viewBox="0 0 34 34"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M0 34.0003H13.4588V24.499C13.4588 22.4853 15.0898 20.8543 17.1035 20.8543C19.1172 20.8543 20.7482 22.4853 20.7482 24.499V34.0003H33.9975V0C15.2211 0 0 15.2211 0 34.0003Z"
                                fill="#CDA274" />
                        </svg>
                        <span class="header__text">
                            Interno
                        </span>
                    </a>
                </div>

                <div class="header__nav">
                    <nav>
                        <a href="index.html">Home</a>
                        <a href="project.html">Project</a>
                        <a href="blog.html">Blog</a>
                    </nav>
                </div>

            </div>
    </header>    
</template>

<script>
export default {
    name: 'HeaderComponent',

    data() {
        return {
            
        };
    },

    mounted() {
        
    },

    methods: {
        
    },
};
</script>

<style lang="scss" scoped>

.header {
  // display: flex;
  // justify-content: space-around;
  &__logo a {
    text-decoration: none;
  }

  &__menu {
    display: flex;
    justify-content: space-between;
    padding-top: 50px;
    padding-bottom: 57px;
    align-items: center;
  }

  &__text {
    color: #292f36;
    font-size: 40px;
    font-style: normal;
    font-weight: 400;
    line-height: 125%;
    padding-left: 10px;
  }

  &__nav a {
    text-decoration: none;
    color: #292f36;
    text-align: center;
    font-family: "Jost";
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 125%;
    padding-left: 40px;
    /* 25px */
  }
}


</style>