     <div class="wrapper">
            <form class="form1" action="https://sites.google.com/view/john-xina/home?authuser=1">
                <div class="formtitle">
                    Ching Cheng _____
                </div>

                <div class="input nobottomborder">
                    <div class="inputtext">
                        What follows
                    </div>

                    <div class="inputcontent">
                        <input type="password" id="password" /><br />
                    </div>
                </div>

                <div class="buttons">
                  <input class="orangebutton" type="submit" value="Login" onclick="passCheck()" />
                </div>
            </form>
        </div>

       <script>
      function checkPassword(){
       if(document.getElementById('password').value == 'Hanji'){
        alert('Correct Password!'); 
          location.href = "https://sites.google.com/view/john-xina/home?authuser=1";
           
         } else {
         alert('dumb');
             alert('dumb');
             alert('dumb');
             alert('dumb');
             alert('dumb');
             alert('dumb');
             alert('dumb');
             alert('dumb');
             alert('dumb');
          return false;
        }
       }
      </script>
