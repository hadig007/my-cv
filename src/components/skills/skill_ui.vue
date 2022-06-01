<template>
  <div class="skills">
    <h3>PROGRAMMING SKILLS</h3>
    <div class="part1">
      <div class="frontend">
        <h6>Front End</h6>
        <ul>
          <li>
            <div class="box">
              <img
                src="https://alfianizzahaja.my.id/assets/img/tekno/js.png"
                alt=""
              />
              <p>Javascript</p>
              <a href="https://www.javascript.com/">Learn More</a>
            </div>
          </li>
          <li>
            <div class="box">
              <img
                src="https://upload.wikimedia.org/wikipedia/commons/f/f1/Vue.png"
                alt=""
              />
              <p>Vue</p>
              <a href="https://vuejs.org/">Learn More</a>
            </div>
          </li>
          <li>
            <div class="box">
              <img
                src="https://cdn-images-1.medium.com/max/1200/1*5-aoK8IBmXve5whBQM90GA.png"
                alt=""
              />
              <p>Flutter</p>
              <a href="https://flutter.dev/">Learn More</a>
            </div>
          </li>
        </ul>
      </div>
      <div class="backend">
        <h6>Backend</h6>
        <ul>
          <li>
            <div class="box">
              <img
                src="@/assets/skills/node.png"
                alt=""
              />
              <p>Node</p>
              <a href="https://nodejs.org/en/">Learn More</a>
            </div>
          </li>
          <li>
            <div class="box">
              <img
                src="@/assets/skills/ex.png"
                alt=""
              />
              <p>Express</p>
              <a href="https://expressjs.com/">Learn More</a>
            </div>
          </li>
          <li>
            <div class="box">
              <img
                src="data:image/png;base64,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"
                alt=""
              />
              <p>Laravel</p>
              <a href="https://laravel.com/">Learn More</a>
            </div>
          </li>
        </ul>
      </div>
    </div>
    <div class="part2">
      <div class="database">
        <h6>Database</h6>
        <ul>
          <li>
            <div class="box">
              <img
                src="https://pbs.twimg.com/profile_images/1255113654049128448/J5Yt92WW_400x400.png"
                alt=""
              />
              <p>MySql</p>
              <a href="https://www.mysql.com/">Learn More</a>
            </div>
          </li>
          <li>
            <div class="box">
              <img
                src="https://www.nurulfikri.com/wp-content/uploads/2020/02/MongoDB-mdb.png"
                alt=""
              />
              <p>MongoDB</p>
              <a href="https://www.mongodb.com/">Learn More</a>
            </div>
          </li>
          <li>
            <div class="box">
              <img
                src="https://raw.githubusercontent.com/hivedb/hive/master/.github/logo_transparent.svg?sanitize=true"
                alt=""
              />
              <p>Hive</p>
              <a href="https://pub.dev/packages/hive">Learn More</a>
            </div>
          </li>
        </ul>
      </div>
      <div class="others">
        <h6>Others</h6>
        <ul>
          <li>
            <div class="box">
              <img
                src="data:image/png;base64,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"
                alt=""
              />
              <p>Github</p>
              <a href="https://github.com/hadig007">Learn More</a>
            </div>
          </li>
          <li>
            <div class="box">
              <img
                src="data:image/png;base64,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"
                alt=""
              />
              <p>Figma</p>
              <a href="https://www.figma.com/">Learn More</a>
            </div>
          </li>
          <li>
            <div class="box">
              <img
                src="data:image/png;base64,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"
                alt=""
              />
              <p>Photoshop</p>
              <a href="https://www.adobe.com/sea/products/photoshop/landpa.html?sdid=12B9DXDJ&mv=search&ef_id=Cj0KCQjw-daUBhCIARIsALbkjSaSEE476cJgdWhQ1Ccu_SzE9KIRhiMs0ssA20uXVn4JNl9bVUy1Xv8aAs7rEALw_wcB:G:s&s_kwcid=AL!3085!3!248235001622!e!!g!!photoshop!703952628!38400836578&gclid=Cj0KCQjw-daUBhCIARIsALbkjSaSEE476cJgdWhQ1Ccu_SzE9KIRhiMs0ssA20uXVn4JNl9bVUy1Xv8aAs7rEALw_wcB">Learn More</a>
            </div>
          </li>
        </ul>
      </div>
    </div>
    <div class="stack">
        <img class="up" src="https://icons.veryicon.com/png/o/miscellaneous/unionpay-digital-marketing/up-arrow-thin.png" alt="">
        <h2>TechStack</h2>
    </div>
  </div>
</template>

<style scoped>
.skills {
  padding: 1rem;
  display: flex;
  flex-direction: column;
}
h3,
h6 {
  text-align: center;
  margin: 0;
}
h6 {
  color: rgb(92, 92, 92);
}
.part1{
  display: flex;
  justify-content: center;
  margin-top: 1rem;
}
.part2 {
  display: flex;
  justify-content: center;
}
.frontend, .database {
    margin-right: 1rem;
}
.box {
  box-shadow: 1px 1px 5px 1px rgba(0, 0, 0, 0.1);
  padding: 5px;
  display: flex;
  flex-direction: column;
  width: 60px;
  height: 70px;
  margin: 0.2rem;
  transition: 0.3s;
  border-radius: 4px;
}
.box:hover {
  box-shadow: 1px 1px 5px 1px rgba(0, 0, 0, 0.05);
  padding: 5px;
  display: flex;
  flex-direction: column;
  width: 60px;
  height: 70px;
  margin: 0.2rem;
  border-radius: 4px;
  transform: scale(1.05);
  background-color: rgb(209, 209, 209);
}
ul {
  padding: 0;
  display: flex;
}
h6 {
    font-size: 1rem;
    font-weight: 300;
    /* border-bottom: solid rgb(204, 204, 204) 2px; */
}
li {
  list-style: none;
}
img {
  align-self: center;
  width: 40px;
  height: 40px;
  
}
p {
  margin: 0;
  font-size: 0.8rem;
  text-align: center;
}
a {
  margin-top: -3px;
  font-size: 0.5rem;
  text-align: center;
}
h2 {
    margin: 0;
    font-size: 0.9rem;
    font-weight: normal;
    align-self: center;
    text-align: center;
}
.stack {
    display: flex;
    align-self: center;
    flex-direction: column;
    /* position: absolute; */
    margin-top: -10px ;
    background-color: rgb(111, 219, 255);
}
.up {
    width: 20px;
    height: 20px;
}
</style>