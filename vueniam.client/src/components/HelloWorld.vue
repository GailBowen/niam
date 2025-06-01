<template>
  <div class="container">
    <header>
      <div class="logo-social">
        <img src="../assets/iam_roadsmart_officialprovider.png" width="125" height="125" />
        
        <div class="social-icons">
          <i class="fab fa-facebook-f"></i>
          <i class="fab fa-twitter"></i>
          <i class="fab fa-linkedin-in"></i>
          <i class="fab fa-instagram"></i>
        </div>
      </div>
      <h1>Newbury Advanced Motorists</h1>
      <nav>
        <ul>
          <li>Home</li>
          <li>About us</li>
          <li>Our courses</li>
          <li>Events</li>
          <li>News</li>
          <li>Road tips</li>
          <li>Contact us</li>
          <li class="join-group">Join our group</li>
          <li><i class="fas fa-search"></i></li>
        </ul>
      </nav>
    </header>

    <main>
      <ul class="questions">
        <li><strong>Are you looking to become a safer, more skilful and more confident driver?</strong></li>
        <li><strong>Are you fully conversant with the current rules of the road as detailed in the latest version of the Highway Code?</strong></li>
        <li><strong>Do you feel you've developed some bad habits since you took your driving test?</strong></li>
        <li><strong>Are you happy driving on all types of roads in various weather conditions?</strong></li>
        <li><strong>Are you looking to extend your years behind the wheel of a vehicle by becoming a more observant driver with a great sense of anticipation?</strong></li>
        <li><strong>Do you wish to obtain a nationally recognised driving qualification accredited by the DVSA?</strong></li>
      </ul>
      <p class="info">
        If your answer to one or more of these questions is “yes” then please go to the <span class="link">About us</span> and <span class="link">Our courses</span> tabs to find out more on how we can help you achieve that aim.
      </p>
      <h2>Enquiries</h2>
      <p>
        Are you a local group or organisation whose members would like to learn more about Advanced driving? If so, then please let us know as
      </p>
    </main>
  </div>
</template>

<script>
  export default {
    name: "NewburyAdvancedMotorists",
  };
</script>

<style scoped>
  .container {
    font-family: Arial, sans-serif;
    background: #fff;
    color: #222;
    max-width: 900px;
    margin: 0 auto;
    padding: 20px 0 40px 0;
  }

  header {
    border-bottom: 2px solid #e0e0e0;
    margin-bottom: 20px;
  }

  .logo-social {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .logo {
    width: 120px;
    margin-bottom: 10px;
  }

  .social-icons i {
    color: #00a1e0;
    margin-right: 10px;
    font-size: 1.2em;
  }

  h1 {
    font-size: 2em;
    margin: 10px 0 0 0;
  }

  nav ul {
    display: flex;
    flex-wrap: wrap;
    list-style: none;
    padding: 0;
    margin: 10px 0 0 0;
    background: #00a1e0;
    border-radius: 4px;
  }

    nav ul li {
      padding: 10px 18px;
      color: #fff;
      cursor: pointer;
    }

      nav ul li.join-group {
        font-weight: bold;
        background: #fff;
        color: #00a1e0;
        border-radius: 4px;
        margin-left: auto;
      }

      nav ul li i {
        font-size: 1.1em;
      }

  .questions {
    margin-top: 30px;
    margin-bottom: 20px;
  }

    .questions li {
      margin-bottom: 12px;
      font-size: 1.1em;
    }

  .info {
    margin-bottom: 30px;
  }

  .link {
    color: #00a1e0;
    text-decoration: underline;
    cursor: pointer;
  }

  h2 {
    font-size: 1.3em;
    margin-top: 20px;
    margin-bottom: 8px;
  }
</style>
