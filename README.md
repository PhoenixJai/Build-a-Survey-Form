# Build-a-Survey-Form
<header class="header">
<h1 id="title">Brandywine School District Post Highschool Survey</h1>
<p id="description">The district is conducting a survey to see what most of the students plan to do after high school.</p>
</header>
<br>

<form id="survey-form">
  <label id="name-label">Name</label>
<input type="text" id="name" placeholder="Enter your name" required></input>
<br>
<br>
<label id="email-label">Email</label>
<input type="email" id="email" placeholder="Enter your email" class="form-control" required></input>
<br>
<br>
<label id="number-label" for="number">Age</label>
<input type="number" name="age" id="number" class=:form-control; placeholder="Age" min="13" max="18"</input>

<div class="form-group">
  <p>Pick your current high school</p>
  <select id="dropdown" name="High school">
    <option disabled value selected>Select your school</option>
    <option value="Mount">Mount Pleasant High school</option>
    <option value="Brandywine">Brandywine High school</option>
    <option value="Concord">Concord High school</option>
  </select>
    </div>

  <div class="form-group">
    <p>What are your plans after you graduate? (Check all that apply)</p>
    
    <div id="f-plans">
    <input name="plans" value="Go to college" type="checkbox" class="input-checkbox">
      <label for="plans">Go to college</label>
    
      
      <br>
    <input name="plans" value="Go to trade school" type="checkbox" class="input-checkbox">
    <label for="plans">Go to trade school
      </label>        
     
      <br>
     <input name="plans" value="Get a job" type="checkbox" class="input-checkbox">
    <label for="plans"> Get a job
                </label>
      <br>
       
    
    <input name="plans" value="Other" type="checkbox" class="input-checkbox">
    <label for="plans"> Other
       </label
      </div>
      </div>
      
<div class="form-group">
     <p>Any additional comments?</p>      <textarea id="comments" class="input-textarea" name="comment"></textarea>
      </div>
      
<div class="form=group">
  <p>Did you enjoy this survey?</p>
  <input name="feelings" value="Yes" type="radio" class="input-radio"
         <label for="feel">Yes</label>
      
<div class="form-group">
  <input name="feelings" value="not-sure" type="radio" class="input-radio"
  <label for="feel">I'm not sure</label>
    
<div class="form-group">
  <input name="feelings" value="No" type="radio" class="input-radio"
         <label for="feel">No</label>
    </div>
    <br>
      
<div class="form-group">
  <button type="submit" id="submit" class="submit-button">Submit</button>
</form>
