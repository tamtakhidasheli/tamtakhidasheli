- 👋 Hi, I’m @tamtakhidasheli
- 👀 I’m interested in programming.
- 🌱 I’m currently learning HTML and CSS.
- 📫 How to reach me? Email - tamta.khidasheli.1@iliauni.edu.ge

<!---
tamtakhidasheli/tamtakhidasheli is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<link rel="stylesheet" href="styles.css">
<html lang="en">
  <head>
    <title>Survey Form</title>
    </head>
  <body>
    <header>
    <h1 id="title">
      freeCodeCamp Survey Form
    </h1>
    <p id="description">
      Thank you for taking the time to help us improve the platform
    </p>
    </header>
    <main>

    <form id="survey-form">
      <br>
      <label for="name" class="space" id="name-label"><b>Name</b></label>
      <br>
      <br>
      <input id="name" type="text" name="name" placeholder="Enter your name" required class="space"></input>
      <br>
      <br>
      <label for="email" id="email-label" class="space"><b>Email<b></label>
      <br>
      <br>
      <input id="email" type="email" name="email" placeholder="Enter your Email" required class="space"></input>
      <br>
      <br>
      <label for="number" id="number-label" class="space"><b>Age</b>(Opional)</label>
      <br>
      <br>
      <input id="number" type="number" name="number" placeholder="Age" required min="10" max="100" class="space"></input>
      <br>
      <br>
      <label for="dropdown" id="role" class="space" ><b>Which option best describes your current role?</b></label>
      <br>
      <br>
      <select id="dropdown" class="space">
        <option placeholder="Select current role">Select current role</option>
        <option value="Student">Student</option>
        <option value="Full time job">Full time job</option>
        <option value="Full time learner">Full time learner</option>
        <option value="Prefer not to say">Prefer not to say</option>
        <option value="Other">Other</option>
        </select>
        <br>
        <br>
        <label for="recommend" id="recommend" class="space"><b>Would you recommend freeCodeCamp to a friend?</b></label>
        <br>
        <br>
        <input id="recomend" type="radio" id="Definitely" value="Definitely" name="describe"> 
        <label for="recomend">Definitely</label>
        <br>
        <input id="recomend" type="radio" value="Maybe" name="describe"> 
         <label for="recomend">Maybe</label>
        <br>
        <br>
        <label for="dropdown" class="space" id="feature"> <b>What is your favorite feature of freeCodeCamp?</b></label>
        <br>
        <br>
        <select id="dropdown" class="space">
          <option value="Select an option">Select an option</option>
          <option value="Challenges">Challenges</option>
          <option value="Projects">Projects</option>
          <option value="Community">Community</option>
          <option value="Open Source">Open Source</option>
          </select>
          <br>
          <br>
          <label for="improve" id="improve" class="space"><b>What would you like to see improved?(Check all that apply)</b></label>
          <br>
          <br>
          <input id="checkboxs" class="radio-button" type="checkbox" name="improve" value="front">
          <label for="checkbox">Front-end Projects</label>
          <br>
          <input id="checkboxs" class="radio-button" type="checkbox" name="improve" value="back">
          <label for="checkbox">Back-end Projects</label>
          <br>
          <input id="checkboxs" class="radio-button" type="checkbox" name="improve" value="Data Visualization">
          <label for="checkbox">Data Visualization</label>
          <br>
          <input id="checkboxs" class="radio-button" type="checkbox" name="improve" value="Challenges">
          <label for="checkbox">Challenges</label>
          <br>
          <input id="checkboxs" class="radio-button" type="checkbox" name="improve" value="Open Source Community">
          <label for="checkbox">Open Source Community</label>
          <br>
          <input id="checkboxs" type="checkbox" class="radio-button" name="improve" value="Gitter help rooms">
          <label for="checkbox">Gitter help rooms</label>
          <br>
           <input id="checkboxs" class="radio-button" type="checkbox" name="improve" value="Videos">
          <label for="checkbox">Videos</label>
          <br>
           <input id="checkboxs" class="radio-button" type="checkbox" name="improve" value="City Meetups">
          <label for="checkbox">City Meetups</label>
          <br>
           <input id="checkboxs" class="radio-button" type="checkbox" name="improve" value="Wiki">
          <label for="checkbox">Wiki</label>
          <br>
           <input id="checkboxs" class="radio-button" type="checkbox" name="improve" value="Forum">
          <label for="checkbox">Forum</label>
          <br>
           <input id="checkboxs" class="radio-button"type="checkbox" name="improve" value="Additional Courses">
          <label for="checkbox">Additional Courses</label>
          <br>
          <br>
          <label for="comments" id="comments" class="space"><b>Any comments or suggestions?</b></label>
          <br>
          <br>
          <textarea id="comments" class="space" type="text" name="comments" placeholder="Enter your comments here..." rows="5" cols="40"></textarea>
          <br>
          <br>
          <button id="submit" type="submit" value="submit" class="submit-button" >submit</button>
          <br>
          <br>

    </main>
    </form>
    </body>
    </html>
