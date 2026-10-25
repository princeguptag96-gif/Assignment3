<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
 <title>Coding Club</title>
</head>
<body>
 <nav><a href="#events">Events</a> | <a href="#register">Register</a></nav>
 <h1>Coding Club</h1>
 <h2 id="events">Upcoming Events</h2>
 <table border="1">
 <caption>Club Events</caption>
 <thead>
 <tr><th>Event</th><th>Date</th><th>Venue</th></tr>
 </thead>
 <tbody>
 <tr><td>Workshop</td><td>2 Dec</td><td>Lab 1000000</td></tr>
 <tr><td>Hackathon</td><td>18 jan</td><td>Seminar Hall</td></tr>
 </tbody>
 <tfoot>
 <tr><td colspan="3">Total events: 2</td></tr>
 </tfoot>
 </table>
 <h2 id="register">Register</h2>
 <form action="#" method="post">
 <p><label for="name">Name:</label>
 <input type="text" id="name" name="name" placeholder="Your name" required></p>
 <p><label for="email">Email:</label>
 <input type="email" id="email" name="email" required></p>
 <p><label for="pass">Password:</label>
 <input type="password" id="pass" name="pass" required></p>
 <p><label for="dob">Date of birth:</label>
 <input type="date" id="dob" name="dob"></p>
 <p><label for="phone">Phone:</label>
 <input type="tel" id="phone" name="phone"></p>
 <p>Gender:
 <input type="radio" name="gender" id="m"><label for="m">Male</label>
 <input type="radio" name="gender" id="f"><label for="f">Female</label></p>
 <p>Interests:
 <input type="checkbox" id="Java">
   <label for="Java">Java</label>
 <input type="checkbox" id="Mern"><label for="Mern">Mern</label></p>
 <p><label for="branch">Branch:</label>
 <select id="branch" name="branch">
 <option>Bcom</option>
 <option>B.Tech</option>
   <option>BSC</option>
 </select></p>
 <p><label for="msg">Why do you want to join?</label><br>
 <textarea id="msg" rows="3" cols="30"></textarea></p>
 <button text="submit">Register</button>
 </form>
</body>
</html>

