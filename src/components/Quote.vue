<template>
  <section>
    <div class="message-bubble">
      <p class="subtitle">Pillzen offers an effortless <br> medication tracking,<br> adherence, communication,<br> and centralized <br> medical information.</p>
    </div>

    <div class="paragraph">
      <p>"Like education, health also needs <br>to be given importance"<br>-Shiv Nadar</p>
    </div>

    <div class="image-container">
      <img src="/assets/PhotoFunia-1689611954 1.png" alt="Your Image" class="image" />
    </div>
  </section>
</template>

<style scoped>
  section {
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
    margin-top: 30px;
    margin-bottom: 30px;
  }

  .message-bubble {
    background-color: rgb(12, 168, 147);
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
    border-radius: 10px;
    padding: 1.5rem;
    z-index: 10;
    color: rgb(15, 14, 14);
    position: relative;
    max-width: 500px;
    
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
    font-family: 'Dancing Script', cursive;
    font-size: 25px;
    /* margin-bottom: 30px; */
    margin-left: 40px;
    text-align: center;
  }

  .image-container {
    display: flex;
    justify-content: center;
    /* Center the image horizontally */
  }

  .image {
    width: 150px;
    height: auto;
    border-radius: 10px;
    margin: 0 10px; /* Add some spacing between the images */
  }

  @media (max-width: 768px) {
    .message-bubble {
      max-width: 100%;
      text-align: center;
    }

    .paragraph {
      font-size: 18px;
      margin-top: 20px;
    }
    section{
      flex-direction: column;
    }

    .image-container {
      flex-wrap: wrap; /* Allow the images to wrap to the next line on smaller screens */
    }

    .image {
      margin: 10px; /* Add spacing between the images on smaller screens */
    }
  }
</style>
