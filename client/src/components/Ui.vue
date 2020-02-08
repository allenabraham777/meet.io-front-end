<template>
  <div id="Ui">
      <div class="row">
        <div class="mic-wrapper">
          <div class="mic"><img src="" alt="Mic"></div>
          <div class="begin-wrapper">
            <button class="begin-button">Begin</button>
          </div>
        </div>
        <div class="dialog-wrapper">
          <div class="logo">meet.io</div>
          <div class="poll-container">
            <button class="poll-button">Create Poll</button>
          </div>
          <div class="text">
            <div class="speech-text">
              <!--Text Goes Here-->
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus, incidunt rem eius eveniet magni quia quo numquam ipsam in beatae dolore officia aliquid saepe obcaecati nobis eaque quis! Ea cumque quos natus, saepe fugit omnis officia sequi quo. A odio voluptatibus nostrum ipsam provident quia nulla perspiciatis atque ut eveniet quod placeat accusamus impedit aspernatur eius reprehenderit praesentium quibusdam, enim itaque? Odit ab aliquam illum inventore! Sit fuga amet voluptate, neque dolores voluptatum unde officia quo nisi ullam harum totam suscipit consequuntur enim eligendi at, esse quas eaque beatae consectetur maiores. Autem voluptatum dolorem necessitatibus eveniet neque suscipit est recusandae ut voluptas cumque nostrum sequi, delectus cupiditate at eaque quam aut omnis labore ad molestias fugit. Doloribus fuga quis, quidem at laborum eum accusamus ab molestias tempora. Incidunt, impedit harum hic, unde autem quidem eos nesciunt blanditiis aut iure corrupti delectus quia reiciendis sit maiores aliquam facere consequatur, ipsa voluptatibus? Quos aspernatur numquam molestias officia odio quibusdam consequatur temporibus modi rem excepturi veniam, laudantium doloremque et dignissimos eos commodi quis molestiae quam unde vel minus mollitia. Minus quis eius inventore ad quos voluptatem itaque rem non sequi doloribus, numquam doloremque reiciendis debitis eligendi architecto nihil distinctio labore dolorem explicabo exercitationem?
            </div>
          </div>
          <div class="summerize-container">
            <button class="summerize-button">Summerize</button>
          </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Ui',
  components: {
  }
}
</script>

<style>
#Ui{
  margin: 0;
  padding: 0;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}
.row{
  display: flex;
  height: 100%;
}
.mic-wrapper{
  width: 60%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
}
.mic{
  height: 20rem;
  width: 20rem;
  background: #76BBB4;
  border-radius: 50%;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
.begin-button {
  height: 5rem;
  width: 15rem;
  background: none;
  border: 3px solid #76BBB4;
  border-radius: 5rem;
  font-size: 1.8rem;
  color: #76BBB4;
  font-weight: 1000;
  cursor: pointer;
  outline: none;
  transition: all 0.5s;
}

.begin-button:hover {
  background: #76BBB4;
  color: #ffffff;
}
.dialog-wrapper{
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  background: #173F5F;
  width: 40%;
  color: #ffffff;
  padding: 2rem;
  font-size: 1.2rem;
}

.logo {
  width: 100%;
  font-size: 3rem;
  text-align: right;
}

.poll-button,.summerize-button{
  height: 5rem;
  width: 20rem;
  font-size: 2rem;
  background: none;
  border: solid 2px #ffffff;
  color: #ffffff;
  border-radius: 2.5rem;
  transition: all 0.5s;
  cursor: pointer;
}

.poll-button:hover,.summerize-button:hover{
  background: #ffffff;
  color: #173F5F;
}

.speech-text {
  max-width: 35rem;
  border: solid 2px #ffffff;
  height: 35rem;
  padding: 3rem;
  font-size: 1.8rem;
  line-height: 2.5rem;
  text-align: justify;
  overflow-y: scroll;
}
</style>
