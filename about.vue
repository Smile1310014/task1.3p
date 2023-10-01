<template>
    <div>
      <header>
        <section class="about-me">
          <h2>About Me</h2>
          <p>
            Greetings, I'm Prabhjit Singh, a dedicated web developer currently pursuing a Bachelor of IT at Deakin University. My academic journey, combined with my passion for web development, has laid a solid foundation for crafting innovative digital solutions.</p>
          <p>
            As a student of IT at Deakin University, I've had the privilege of delving into the intricacies of technology and its profound impact on our digital world. The knowledge and skills acquired during my academic journey have empowered me to approach web development with both creativity and technical expertise.</p>
          <p> 
            I invite you to explore my portfolio, where you'll find a diverse collection of web development projects that reflect my dedication to this dynamic field. </p>
        </section>
      </header>
    </div>
  </template>
  
  <script>
  export default {
    name: 'about-me',
  };
  </script>
  
  <style scoped>
  .about-me {
    background-color: rgb(201, 238, 166);
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    padding: 2rem; /* Adjust padding as needed */
    margin: 76rem; /* Add margin to create space around the section */
    text-align: left;
    position: relative;
    top: -1100px;
}

  .about-me h2 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    text-align: left;
  }

  p{
    font-size: 24px;
  }
  
  /* Add any CSS styles specific to this component here */
  </style>
  