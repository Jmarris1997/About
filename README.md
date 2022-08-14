 -0,0 +1,25 @@
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>My Contact</title>
  </head>
  <body>
    <h1>My Contact Details</h1>
    <ul>
      <li>Contact me:+2348146919602</li>
      <li>Email Address: stellamarrisjohn18@gmail.com</li>
      <li>Address: Ekeki yenegoa, Bayelsa State</li>
    </ul>
    <hr>
    <form  action="mailto:stellamarrisjohn18@gmail.com" method="post" enctype="text/plain">
      <label for="">Your Name</label>
      <input type="text" name="YourName" value=""><br>
      <label for="">Your Email</label>
      <input type="email" name="YourEmail" value=""><br>
      <label>Your Message:</label><br>
      <textarea name="YourMessage" rows="10" cols="30"></textarea><br>
      <input type="submit" name="">
    </form>
  </body>
</html>
 17  
Web development/Html-personal site/hobbis.html
@@ -0,0 +1,17 @@
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>My Hobbies</title>
  </head>
  <body>
    <h3>My Hobbies</h3>
    <ol>
      <li>Singing</li>
      <li><a href="https://web.facebook.com/photo.php?fbid=1686880598370136&set=pb.100011446362101.-2207520000..&type=3">Dancing</a></li>
      <li>Studying</li>
      <li><a href="https://web.facebook.com/profile.php?id=100063544085345">Making Money</a></li>
      <li> <a href="https://web.facebook.com/photo.php?fbid=627863397605200&set=t.100011446362101&type=3">Execising</a> </li>
    </ol>
  </body>
</html>
 123  
Web development/Html-personal site/index.html
@@ -0,0 +1,123 @@
<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <title>❤Stella personal site</title>
</head>

<body>
  <table cellspacing="20">
    <tr>
      <td><img height="200" src="stella1.png" alt="Stellamarris Picture">
      </td>
      <td>
        <h1>JOHN STELLAMARRIS</h1>
        <p><em><strong>Web Developer</strong></em></p>
        <p>My name is <strong><a href="https://web.facebook.com/stellamarris.john">JOHN STELLAMARRIS</a></strong>.Am from anambra state umoukpu awka south,local goverment. I started coding in <strong>febuary 2022</strong> and it has been a wonderfull
          experience </p>
      </td>
    </tr>
  </table>

  <hr>
  <h3> <strong>STUDY PLAN</strong></h3>
  <ul>


    <li>Learn Coding</li>
    <li><a href="https://elladelightb.com/">Build Website</a></li>
    <li>Build an App</li>
  </ul>
  <hr>
  <h3>Classes Planned Out</h3>

  <table>
    <thead>
      <tr>
        <th>Levels</th>
        <th>Classes</th>
      </tr>
    </thead>
    <tbody>

      <tr>
        <td>Level One</td>
        <td>Angella yu complete web Development bootcamp</td>
      </tr>
      <tr>
        <td>Level Two</td>
        <td>The Complete Phyton Program</td>
      </tr>
      <tr>
        <td>Level Three</td>
        <td>Complete ios App Development bootcamp</td>
      </tr>
    </tbody>
    <tfoot>

    </tfoot>
</table>
<hr>
    <table cellspacing="10" >
      <h3>SKILLS</h3>
      <tr>
        <td>
          <table >
            <td>
              <tr>
                <td>Coking</td>
                <td>⭐️⭐️⭐️⭐️⭐️</td>
              </tr>
              <tr>
                <td>Marketing</td>
                <td>⭐️⭐️⭐️⭐️⭐️</td>
              </tr>
              <tr>
                <td>Baking</td>
                <td>⭐️⭐️⭐️⭐️⭐️</td>
              </tr>

              <tr>
                <td>Typing</td>
                <td>⭐️⭐️⭐️☆☆</td>

              </tr>
          </table>
        </td>
        <td>
          <table >
            <tr>
              <td>Dancing</td>
              <td>⭐️⭐️☆☆☆</td>
            </tr>
            <tr>
              <td>Coding</td>
              <td>⭐️⭐️☆☆☆</td>
            </tr>
            <tr>
              <td>Singing</td>
              <td>⭐️☆☆☆☆</td>
            </tr>

            <tr>
              <td>Content creating</td>

              <td>⭐️☆☆☆☆</td>
              </tr>
            </table>
        </td>

        </tr>
    </table>



    <hr>
    <a href="hobbis.html">My Hobbies</a>
    <p>
      <a href="contact.html">Contact Information</a>
    </p>
</body>

</html>
