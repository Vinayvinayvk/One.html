# One.html
Html file 
<!DOCTYPE html>

<html>
<head>
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
  <title>Hello, World!</title>
</head>
<body>
  <from action="submission.html">
    <h1>student appliction form</h1>
    <feeldset>
      <table>
        <tr>
          <td>
            <label for="fname">First name</label>
          </td>
          <td>:</td>
          <td>
            <input type="text" placeholder="first name" id="fname" name="text fname" autofocus required>
          </td>
        </tr>
        <tr>
          <td>
            <label for="iname">Last name</label>
          </td>
          <td>:</td>
          <td>
            <input type="text" placeholder="last name" id="iname" name="text iname" required>
          </td>
        </tr>
        <tr>
          <td>
            <label for="dob">Date of birth</label>
          </td>
          <td>:</td>
          <td>
            <input type="datetime-local">
          </td>
        </tr>
        <tr>
          <td>
            <label for="gen">gender</label>
          </td>
          </tr>
          <tr>
            <td>
              <input type="radio" name="Gender" value="male">Male
              <input type="radio" name="Gender" value="femal">Femal
          </td>
        </tr>
          <tr>
            <td>
              <label for="hob">Hobbies</label>
            </td>
            <td>:</td>
            <td>
              <input type="checkbox" value="Chess">Chess
              <input type="checkbox" value="foot ball">Foot ball
              <input type="checkbox" value="tennies">Tennies
              <input type="checkbox" value="carom">carom
            </td>
          </tr>
          <tr>
            <td>
              <label for="courrces">Cources</label>
            </td>
            <td>:</td>
            <td>
              <select name="cources" id="cources">
              <option value="select">---Seclect Courcs---</option>
              <option value="select" value="java">Java</option>
                <option value="select" value="html">HTML</option>
              <option value="select" value="Pythone">Pythone</option>
              <option value="select" value="C">C</option>
                </select>
            </td>
            <td>
              <label for="uniname">Univarsity</label>
            </td>
            <td>:</td>
            <td>
              <select name="univarsity" id="univarsity">
                <option value="select">---select univarsity---</option>
                <option value="sk univarsity">SK univarsity</option>
                <option value="krishna univarsity">Krishna univarsiry</option>
                <option value="yogi vemana univarsity">Yougi vemana univarsity</option>
                <option value="kakatiya univarsity">Kakatiya univarsity</option>
                <option value="andhra univarsity">andhra univarsity</option>
                <option value="acharya nagarjuna univarsity">acharya nagarjuna univarsity</option>
                <option value="adikavi nanayya univarsity">adikavi nanayya univarsity</option>
                <option value="dr. ambedkar univarsity">dr.ambedkar univarsity</option>
              </select>
            </td>
          </tr>
        <tr>
          <td>
              Mobile number
          </td>
          <td>:</td>
          <td>
            <input type="text" placeholder="Mobile number" maxlength="10">
          </td>
        </tr>
        <tr>
          <td>
            <label for="email">Email address</label>
          </td>
          <td>:</td>
          <tr>
            <td>
              <input type="email" placeholder="Enter Email">
            </td>
          </tr>
        </tr>
        <tr>
          <td>
            <aligan="center">
              <closepon="0.3">
                <input type="submit" value="submit">
          </td>
            </tr>
      </table>
    </feeldset>
  </from>
</body>
</html>
