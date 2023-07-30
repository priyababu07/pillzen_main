<template>
  <br>
  <div class="container" id="services">
    <br>
    <div class="row g-3 justify-content-center">
      <div class="card">
        <h2>Our Goal</h2>
        <br>
        <p>Interactions with patients, clinical diagnoses, and potential treatments can be augmented and documented more accurately and in near real-time</p>
      </div>

      <div class="card">
        <h2>Our Vision</h2>
        <br>
        <p>To develop a safe world with health and wealth. To help in the development of effective and interpersonal relationship skills with patients, doctors, and colleagues</p>
      </div>

      <div class="card">
        <h2>Our Mission</h2>
        <br>
        <p>Managing one's own medicines is a skill that is necessary for successful independent living.</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
  box-shadow: 0px 30px 30px -4px rgba(0, 0, 0, 0.1), 0px 4px 8px -4px rgba(0, 0, 0, 0.3);
  transition: box-shadow 0.3s ease;
  max-width: 298px;
  margin-right: 30px;
  text-align: center;
  padding: 2px;
}

.row.g-3 {
  gap: 10px;
  /* Adjust the gap value as needed to set the spacing between cards */
}

p {
  margin-left: 10px;
  margin-right: 10px;
  font-size: 20px;
}

h2 {
  text-align: center;
  margin-bottom: 20px;
  margin-top: 20px;
  font-weight: bold;
}

.card:hover {
  transform: translateY(-10px);
  cursor: pointer;
  background-color: rgb(12, 168, 147);
}

@media (max-width: 768px) {
  .card {
    display: flex;
    flex-direction: column;
    justify-content: center; /* Center the cards vertically */
    align-items: center; /* Center the cards horizontally */
    margin-right: 0; /* Remove the right margin on smaller screens to ensure cards are in the same row */
  }

  .row.g-3 {
    gap: 0; /* Remove the gap between cards on smaller screens */
  }

  h2 {
    text-align: center;
    margin-bottom: 20px;
    font-weight: bold;
    margin-top: 20px;
  }

  .card:hover {
    transform: translateY(-10px);
    cursor: pointer;
    background-color: rgb(12, 168, 147);
  }

  #card {
    display: flex;
    justify-content: center;
  }
}
</style>
