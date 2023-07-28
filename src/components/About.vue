<!-- "WhyMedicaze.vue" -->
<template>
    <section>
      <p>
        
      </p>
      <div class="background-container">
        <div class="about">
          <h2>Why Medicaze ?</h2>
          <ul>
            <li>seamless integration with a medical box simplifies the sharing of diagnostic information, eliminating the need for complex APIs.</li>
            <li>Pre-filled medication box and reminders enhance medication management and ensure adherence to prescribed regimens.</li>
            <li>The platform provides a centralized system for retrieving Electronic Health Records (EHR) data, saving time and effort for patients.</li>
            <li>Integration of medication adherence data and medical records improves communication and collaboration between patients and healthcare providers.</li>
            <li>User-friendly interface, pre-filled medication box, and centralized access to EHR data reduce complexity and cost, saving time and effort in managing medications and communicating with healthcare providers.</li>
          </ul>
        </div>
      </div>
    </section>
  </template>
  
  <style scoped>
    .background-container {
      background-image: url("/assets/image 44.png");
      height: 100vh;
      background-size: cover;
      background-position: center;
      position: relative;
      display: flex;
      justify-content: center; /* Center content horizontally */
      /* Center content vertically */
    }
  
    .background-container::before {
      content: "";
      display: block;
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: 1;
    }
  
    .about {
      position: relative;
      z-index: 2;
      padding: 20px;
      color: #000;
    }
  
    h2 {
      text-align: center; /* Center the text inside the <h1> tag */
    }
  
    ul {
      padding-left: 20px; /* Add left padding to the list items */
    }
  
    li {
      margin-bottom: 10px; /* Add some vertical spacing between list items */
    }
  
    /* Responsive styles */
    @media screen and (max-width: 768px) {
      ul {
        padding-left: 0; /* Remove left padding on smaller screens */
      }
  
      li {
        margin-bottom: 5px; /* Reduce vertical spacing on smaller screens */
      }
    }
    section{
      margin-top:20px
    }
  </style>