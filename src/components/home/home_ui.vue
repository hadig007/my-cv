<template>
  <div class="full">
    <div v-if="this.$store.state.screen === 'profile'" class="content1">
      <div class="kiri">
        <img class="poto" src="@/assets/image7.png" alt="" />
        <h2>Contact</h2>
        <ul>
          <li>
            <img src="@/assets/icon/Circled_Envelope.png" alt="" />
            <p>jtgunawan007@gmail.com</p>
          </li>
          <li>
            <img src="@/assets/icon/WhatsApp.png" alt="" />
            <p>+6285361585645</p>
          </li>
          <li>
            <img src="@/assets/icon/Instagram.png" alt="" />
            <p>@hadig.dev</p>
          </li>
          <li>
            <img src="@/assets/icon/Twitter_Circled.png" alt="" />
            <p>@hadig007</p>
          </li>
          <li>
            <img src="@/assets/icon/LinkedIn_Circled.png" alt="" />
            <p>linkedin/in/hadig007</p>
          </li>
        </ul>
      </div>
      <div class="kanan">
        <div class="head">
          <h1>Hadi Gunawan Tambunan</h1>
          <p>Fullstack Web & Mobile Developer</p>
          <div class="line"></div>
        </div>
        <div class="teks">
          <p>Hi there</p>
          <div class="space"></div>
          <p>
            I’am Hadi Gunawan and I am always open to new knowledge, especially
            in the realm of technology that supports my skills.
          </p>
          <div class="space"></div>
          <p>
            I have studied programming for more than 2 years and chose web and
            mobile development as a career choice.
          </p>
        </div>
      </div>
    </div>
    <div class="content2" v-if="this.$store.state.screen === 'skills'" >
    <Skill_ui/></div>
  </div>
</template>

<script>
import Skill_ui from "../skills/skill_ui.vue";
export default {
  components: {
    Skill_ui
},
  data() {
    return {
      screen: "home",
      currentShow: "content2",
    };
  },
};
</script>

<style scoped>
.full {
  margin: auto;
  margin-top: 150px;
  width: 650px;
  height: 400px;
  background-color: white;
  border-radius: 4px;
  display: flex;
  flex-direction: column;
}
.poto {
  width: 150px;
}
img {
  width: 20px;
  margin-right: 5px;
}
h2 {
  margin-top: 1rem;
  margin-bottom: -0.5rem;
}
h1 {
  margin: 0;
}
ul {
  padding: 0;
  margin-top: 0.5rem;
}
li {
  list-style: none;
  display: flex;
}
.kiri {
  margin: 1rem 3rem;
}
.kanan {
  margin: 1rem 3rem 0 0;
  width: 350px;
}
p {
  margin: 0;
  font-size: 0.75rem;
  color: grey;
}
.content1 {
  display: flex;
}
.line {
  height: 1px;
  width: 30px;
  background-color: grey;
  align-self: center;
  margin: 0.5rem;
}
.space {
  height: 10px;
}
.head {
  margin-top: 2rem;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.teks {
  margin-top: 3.5rem;
}
.teks p {
  color: black;
  font-size: 0.9rem;
}
</style>