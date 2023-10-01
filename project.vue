<template>
    <div>
      <header>
        <section class="project-details">
          <h2>Project Details</h2>
          <p>
            Welcome to my project portfolio. Here you can explore various web development projects that I have worked on. Each project represents a unique challenge and an opportunity to learn and innovate.
          </p>
          <p>
            Skills that I learn from this project are as follows:<br><br>
            1. HTML <br>
            2. CSS3 <br>
            3. JAVASCRIPT <br>
            4. VUE.JS<br>
            5. NODE.JS<br>

          </p>
        </section>
      </header>
    </div>
  </template>
  
  <script>
  export default {
    name: 'project-details',
  };
  </script>
  
  <style scoped>
  .project-details {
    background-color: rgb(201, 238, 166);
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    padding: 2rem; /* Adjust padding as needed */
    margin: 76rem; /* Add margin to create space around the section */
    text-align: left;
    position: relative;
    top: -1100px;
}

  .project-details
   h2 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    text-align: left;
  }

  p{
    font-size: 24px;
  }
  
  /* Add any CSS styles specific to this component here */
  </style>