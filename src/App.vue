<template>
  <div id="app">
    <Main />
  </div>
</template>

<script>
import Main from './pages/main'

export default {
  name: 'App',
  components: {
    Main,
  }
}
</script>

<style lang="scss">
.container {
  margin: auto;
  width: 117rem;
}

@font-face {
  font-family: JosefinSans-Bold;
  src: local('JosefinSans-Bold'),
  url("./assets/fonts/JosefinSans-Bold.ttf");
}
@font-face {
  font-family: JosefinSans-Regular;
  src: local('JosefinSans-Regular'),
  url("./assets/fonts/JosefinSans-Regular.ttf");
}
@font-face {
  font-family: JosefinSans-SemiBold;
  src: local('JosefinSans-SemiBold'),
  url("./assets/fonts/JosefinSans-SemiBold.ttf");
}
@font-face {
  font-family: JosefinSans-Italic;
  src: local('JosefinSans-Italic'),
  url("./assets/fonts/JosefinSans-Italic.ttf");
}
@font-face {
  font-family: Alegreya-Regular;
  src: local('Alegreya-Regular'),
  url("./assets/fonts/Alegreya-Regular.ttf");
}
@font-face {
  font-family: Alegreya-Bold;
  src: local('AlegreyaSans-Bold'),
  url("./assets/fonts/Alegreya-Bold.ttf");
}
@font-face {
  font-family: AbrilFatface-Regular;
  src: local('AbrilFatface-Regular'),
  url("./assets/fonts/AbrilFatface-Regular.ttf");
}
@font-face {
  font-family: CircularStd-Book;
  src: local('CircularStd-Book'),
  url("./assets/fonts/CircularStd-Book.ttf");
}


ul, li {
  list-style-type: none;
}

body {
  background-color: #E5E5E5;
}
:root {
  --fontSize: .62500vw;
}
html,
body {
  margin: 0;
  padding: 0;
  font-style: normal;
  font-size: var(--fontSize);
}
a {
  text-decoration: none;
  color: black;
}
</style>
