<template>
  <section id="about">
      <br>
    <h2>
      <strong>About Us</strong>
    </h2>

    <div class="content-wrapper">
      <div class="content">
        <img src="/assets/about.png" alt="" class="about-image-desktop">
        <p>
          Our groundbreaking solution simplifies medication tracking and promotes adherence. Patients can easily monitor
          and manage their medication schedules while fostering communication with healthcare providers. Retrieval of EHR
          data enhances medication management. This addresses challenges faced by older individuals, reducing errors and
          streamlining record-keeping and communication .
        </p>
      </div>
      <button><router-link to="/about" style="text-decoration: none; color: black;">Learn More</router-link></button>
    </div>
  </section>
</template>

<style scoped>
section {
  margin-left: 10px;
  margin-top: 6%;
}

h2 {
  text-align: center;
  margin-bottom: 20px;
}

button {
  background-color: chocolate;
  color: aliceblue;
  border-radius: 30px;
  border: none;
  margin-bottom: 20px;
  padding-top: 10px;
  padding-left: 10px;
  padding-right: 10px;
  padding-bottom: 10px;
  
}

.content-wrapper {
  display: flex;
  flex-direction: column; /* Stack the content vertically */
  align-items: center; /* Center the content horizontally */
  margin-left: 10px;
  margin-right: 10px;
}

.content {
  display: flex;
  flex-direction: row; /* Align content in row manner by default */
  align-items: flex-start; /* Align items to the top */
}

.about-image-desktop {
  max-width: 300px; /* Adjust the width of the image as needed */
  margin-right: 20px; /* Add some spacing between the image and paragraph in desktop view */
}

p {
  font-size: larger;
  line-height: 30px;
  flex: 1; /* Allow the paragraph to grow and occupy available space */
}

/* Media query for mobile view */
@media (max-width: 760px) {
  .content-wrapper {
    align-items: center; /* Center the content horizontally in mobile view */
  }

  .content {
    flex-direction: column; /* Stack the content in a column manner for mobile view */
  }

  .about-image-desktop {
      margin-left: auto; /* Push the button to the right side */
      margin-right: auto;
  }

  button {
    margin-left: auto; /* Push the button to the right side */
    margin-right: auto; /* Push the button to the left side */
  }
}
</style>







