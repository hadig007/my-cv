<template>
  <div>
    <nav>
      <ul>
        <li class="prt" @click="profile">
         PROFILE
        </li>
        <li @click="skills">SKILLS</li>
        <li @click="portofolio">PORTOFOLIO</li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  methods: {
    profile(){
      this.$store.state.screen = 'profile'
      console.log(this.$store.state.screen)
    },
    skills(){
      this.$store.state.screen = 'skills'
      console.log(this.$store.state.screen)
    },
    portofolio(){
      this.$store.state.screen = 'portofolio'
      console.log(this.$store.state.screen)
    },
  },
};
</script>

<style scoped>
nav {
  margin-top: -20px;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-self: flex-end;
  width: 100%;
}
ul {
  margin: auto;
  width: 650px;
  display: flex;
  justify-content: center;
  background-color: #00c2ff;
  padding: 0;
  border-radius: 0 0 4px 4px;
}
li {
  list-style: none;
  /* margin: 10px; */
}
li {
  list-style: none;
  padding: 5px 69px;
}
a {
  text-decoration: none;
  font-size: 1.3rem;
  font-weight: bold;
  color: white;
}
.prt {
  background-color: #0093c0;
}
</style>