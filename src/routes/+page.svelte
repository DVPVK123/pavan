<script>
    import Heading from "../lib/components/Heading.svelte";

</script>
<main>

<Heading />

     <!-- <img src="Belloon.1.jpg" />      -->




<div class="container">
     <h2>Registration Form</h2>
     <form action="submit_registration.php" method="post">
         <div class="form-group">
             <label for="username">Username:</label>
             <input type="text" id="username" name="username" required>
         </div>
         <div class="form-group">
             <label for="email">Email:</label>
             <input type="email" id="email" name="email" required>
         </div>
         <div class="form-group">
             <label for="password">Password:</label>
             <input type="password" id="password" name="password" required>
         </div>
         <div class="form-group">
             <label for="confirm_password">Confirm Password:</label>
             <input type="password" id="confirm_password" name="confirm_password" required>
         </div>
         <div class="form-group">
             <label for="full_name">Full Name:</label>
             <input type="text" id="full_name" name="full_name" required>
         </div>
         <div class="form-group">
             <label for="gender">Gender:</label>
             <select id="gender" name="gender" required>
                 <option value="">Select</option>
                 <option value="male">Male</option>
                 <option value="female">Female</option>
                 <option value="other">Other</option>
             </select>
         </div>
         <div class="form-group">
             <label for="birthdate">Date of Birth:</label>
             <input type="date" id="birthdate" name="birthdate" required>
         </div>
         <div class="form-group">
             <button type="submit">Register</button>
         </div>
     </form>
 </div>

</main>

 <style>

main {
          background-color: rgb(220, 201, 176);
          background-image: url("image1.jpg");
          background-size: cover; 
          height: 1000px;
          padding-top: 30px;
          padding-bottom: 10px;
          border-radius: 5px;
}
    
     .container {
         width: 50%;
         margin: auto;
         padding: 20px;
         border: 1px solid #ccc;
         border-radius: 5px;
     }
     .form-group {
         margin-bottom: 20px;
     }
     .form-group label {
         display: block;
         font-weight: bold;
     }
     .form-group input,
     .form-group select {
         width: 100%;
         padding: 10px;
         border: 1px solid #ccc;
         border-radius: 5px;
         box-sizing: border-box;
     }
     .form-group button {
         padding: 10px 20px;
         background-color: #007bff;
         color: #fff;
         border: none;
         border-radius: 5px;
         cursor: pointer;
     }
     .form-group button:hover {
         background-color: #0056b3;
     } 

 </style>