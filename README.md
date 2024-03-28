<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GENL 114</title>
    <link rel="shortcut icon" href="project-management.png" type="image/x-icon">
    <style>

    body{
      background: rgb(229,159,240);
background: linear-gradient(90deg, rgba(229,159,240,0.44870448179271705) 24%, rgba(13,186,203,0.19380252100840334) 57%, rgba(56,106,192,0.4375) 100%);
    }
/* CSS */
.button{
  padding: 0.6em 2em;
  border: none;
  outline: none;
  color: rgb(255, 255, 255);
  background: #111;
  cursor: pointer;
  position: relative;
  z-index: 0;
  border-radius: 10px;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
}

.button:before {
  content: "";
  background: linear-gradient(
    45deg,
    #ff0000,
    #ff7300,
    #fffb00,
    #48ff00,
    #00ffd5,
    #002bff,
    #7a00ff,
    #ff00c8,
    #ff0000
  );
  position: absolute;
  top: -2px;
  left: -2px;
  background-size: 400%;
  z-index: -1;
  filter: blur(5px);
  -webkit-filter: blur(5px);
  width: calc(100% + 4px);
  height: calc(100% + 4px);
  animation: glowing-button-85 20s linear infinite;
  transition: opacity 0.3s ease-in-out;
  border-radius: 10px;
}

@keyframes glowing-button {
  0% {
    background-position: 0 0;
  }
  50% {
    background-position: 400% 0;
  }
  100% {
    background-position: 0 0;
  }
}

.button:after {
  z-index: -1;
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  background: #222;
  left: 0;
  top: 0;
  border-radius: 10px;
}

button{
  margin: 14px;
}
.footer {
    background-color: #f8f9fa; 
    color: #333; 
    padding: 10px; 
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
    background: rgba(0, 0, 0, 0.1);
    color: gray;
    text-align: center;
}

.footer p {
    margin: 1px 0; 
}

.container {
    max-width: 1200px; 
    margin: 0 auto; 
}

.row {
    display: flex;
    flex-wrap: wrap;
}

.col-md-6 {
    flex: 0 0 50%;
    max-width: 50%; 
}


</style>
</head>
<body>
    <h1>GENL 114| Computer Concepts & App</h1><hr><br>

    <p>
        Welcome to GENL 114: Computer Concepts! This interactive textbook is your guide to essential computing principles, covering topics from hardware to algorithms. Click on the buttons below to navigate through each chapter and dive into the world of computer concepts.
    </p><br>


    <table>
      <td>
        <tr><a href="section1.htm" target="_blank" rel="noopener noreferrer"><button class="button" role="button">Section 1</button></a>
        </tr>

        <tr><a href="section2.htm" target="_blank" rel="noopener noreferrer"><button class="button" role="button">Section 2</button></a>
        </tr>

        <tr>
          <a href="section3.htm" target="_blank" rel="noopener noreferrer"><button class="button" role="button">Section 3</button></a>
        </tr>

        <tr>
          <a href="section4.htm" target="_blank" rel="noopener noreferrer"><button class="button" role="button">Section 4</button></a>
        </tr>

        <tr>
          <a href="section5.htm" target="_blank" rel="noopener noreferrer"><button class="button" role="button">Section 5</button></a>
        </tr>

        <tr>
          <a href="section6.htm" target="_blank" rel="noopener noreferrer"><button class="button" role="button">Section 6</button></a>
        </tr>
        
        <tr>
          <a href="section7.htm" target="_blank" rel="noopener noreferrer"><button class="button" role="button">Section 7</button></a>
        </tr>

        <tr>
          <a href="section8.htm" target="_blank" rel="noopener noreferrer"><button class="button" role="button">Section 8</button></a>
        </tr>

        <tr>
          <a href="section9.htm" target="_blank" rel="noopener noreferrer"><button class="button" role="button">Section 9</button></a>
        </tr>

        <tr>
          <a href="section10.htm" target="_blank" rel="noopener noreferrer"><button class="button" role="button">Section 10</button></a>
        </tr>

        <tr><a href="section11.htm" target="_blank" rel="noopener noreferrer"><button class="button" role="button">Section 11</button></a>
        </tr>
      </td>

    </table>
    <footer class="footer">
      <div class="container">
          <div class="row">
              <div class="col-md-6">
                  <p>GENL 114 - Computer Concepts and Applications</p>
                  <p>Instructor: Rindra Marnoel Razafinjatovo</p>
                  <p>Contact: rindra@apiu.edu</p>
              </div>
              <div class="col-md-6">
                  <p>Department of Information Tchnology</p>
                  <p>Asia-Pacific International University</p>
                  <p>Contact: 0969312493	</p>
              </div>
          </div>
      </div>
  </footer>
  
    </body>
</html>
