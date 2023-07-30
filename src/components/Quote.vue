<template>
  <div class="container">
    <div class="message-bubble">
      <p class="subtitle">Pillzen offers an effortless medication tracking,<br> adherence, communication,<br> and centralized <br> medical information.</p>
    </div>
    <section>
      <div class="paragraph">
        <p>"Like education, health also needs to be given importance"<br>-Shiv Nadar</p>
      </div>
      <div class="image-container">
        <img src="/assets/PhotoFunia-16896119541.png" alt="Your Image" class="image" />
      </div>
    </section>
  </div>
</template>

<script setup>
// You can declare variables and props here if needed
</script>

<style scoped>
 @import url('https://fonts.googleapis.com/css2?family=Cedarville+Cursive&display=swap');
.container {
  /* min-height: 100vh; */
  width: 100%;
  display: flex;
  justify-content: center; /* Center the content horizontally */
  align-items: center; /* Center the content vertically */
}

.message-bubble {
  background-color: rgb(12, 168, 147);
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
  border-radius: 10px;
  padding: 1.5rem;
  z-index: 10;
  color: rgb(15, 14, 14);
  position: relative;
  max-width: 320px;
  margin-right: 100px;
  margin-top: 50px;
}

.message-bubble::before {
  content: '';
  position: absolute;
  top: 0;
  left: -8px;
  border-width: 8px 8px 8px 0;
  border-style: solid;
  border-color: transparent rgb(12, 168, 147) transparent transparent;
}

.subtitle {
  font-size: 1.2rem;
  margin-bottom: 1rem;
  font-weight: 200;
}

.paragraph {
  font-family: 'Cedarville Cursive', cursive;
  /* margin-right: 50px; */
  padding-right: 10px;
  /* margin-bottom: 300px; */
  font-size: 25px;
  text-align: center; /* Center the paragraph text */
  padding-top: 50px;

}

.image-container {
  /* margin-bottom: 330px; */
  padding-left: 1rem; /* Add some spacing between the image and the message content */
}

.image {
  width: 150px; /* Adjust the width of the image as per your requirement */
  height: auto;
  border-radius: 10px; /* Add border-radius to make the image rounded */
}

section {
  display: flex;
  flex-direction: row;
}

@media (max-width: 768px) {
  .container {
    flex-direction: column; /* Stack the elements in one after another downward manner */
  }

  .message-bubble {
    max-width: 60%; /* Set the message bubble width to adjust for smaller screens */
    margin-bottom: 15px; /* Adjust the margin for better spacing */
    margin-right: 0;
    margin-top: 15px;
    max-height: 100%;
    width: 220px;
  }

  .paragraph {
    font-size: 18px; /* Adjust the font size for better readability on small screens */
    margin-bottom: 15px; /* Adjust the margin for better spacing */
  }

  section {
    display: flex;
    flex-direction: row;
    margin-left: 10px;
    margin-top: 20px;
  }
}
</style>
