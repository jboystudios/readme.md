# my web page
hello there.
fill free to join me today.
lets explore the world together.
Great things are coming soon.
<title>login</title>
            <div class="button-box">
              <div id="btn"></div>
            <button type="button" class="toggle-btn" onclick="login()">login</button>
            <button type="button" class="toggle-btn" onclick="Register()">register</button>
            </div>
            <form id="login" class="input-group">
            <input type="text" class="input-field" placeholder="user id" required>
            <input type="password" class="input-field" placeholder="Enter password" required>
            <input type="checkbox" class="check-box"><span>remember password</span>
            <button type="submit" class="submit-btn">log in</button>
            </form>
            <form id="Register" class="input-group">
            <input type="text" class="input-field" placeholder="user id" required>
            <input type="password" class="input-field" placeholder="Email" required>
            <input type="password" class="input-field" placeholder="Enter password" required>
            <input type="checkbox" class="check-box"><span>i agree to the terms and conditions</span>
            <button type="submit" class="submit-btn">Register</button>
            </form>
            </div>
            </div>
            
            <script>
            var x = document.getElementById("login");
            var y = document.getElementById("Register");
            var z = document.getElementById("btn");
             function Register(){
               x.style.left = "-400px";
               y.style.left = "50px";
               z.style.left = "110px";
             }
             function login(){
               x.style.left = "50px";
               y.style.left = "450px";
               z.style.left = "0";
             }
            </script>
            
</body>
