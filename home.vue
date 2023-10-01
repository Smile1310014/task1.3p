<template>
  <div>
    <header>
       
        <p> If want to know about me or about my projects <br>you can click on the above provided image and if you want to know <br>somethings else, just drop your name and email with the message <br>that you want to ask</p>

        <section class="home-view">
        <h2>Contact Me</h2>
        <form>
          <div class="form-group">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
          </div>
          <div class="form-group">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
          </div>
          <div class="form-group">
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>
          </div>
          <button type="submit">Submit</button>
        </form>
      </section>
      
    </header>
  </div>
</template>

<script>
export default {
  name: 'home-view',
};
</script>

<style scoped>
.home-view  {
    background-color: rgb(201, 238, 166);
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    padding: 2rem; /* Adjust padding as needed */
    margin: 76rem; /* Add margin to create space around the section */
    text-align: left;
    position: relative;
    top: -1100px;
}
.home-view h2 {
  font-size: 1.5rem;
  margin-bottom: 1rem;
}

.form-group {
  margin-bottom: 1rem;
}

.form-group label {
  display: block;
  font-size: 1rem;
  margin-bottom: 0.5rem;
}

.form-group input[type="text"],
.form-group input[type="email"],
.form-group textarea {
  width: 100%;
  padding: 0.5rem;
  font-size: 1rem;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.form-group textarea {
  resize: vertical;
}

button[type="submit"] {
  background-color: blue;
  color: white;
  border: none;
  border-radius: 5px;
  padding: 0.5rem 1rem;
  font-size: 1rem;
  cursor: pointer;
}

button[type="submit"]:hover {
  background-color: darkblue;
}

p{
    text-align: center;
    position: relative;
    top: 80px;
    font-size: 20px;

    
}
/* Add any CSS styles specific to this component here */
</style>
