# WebTech_Expt4

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- Latest compiled and minified CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Latest compiled JavaScript -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>
    <div class = "row mt-3 " >
        <div class="col-2">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Google_2015_logo.svg/1200px-Google_2015_logo.svg.png" width = "100" height = "50" alt="aa">
        </div>
        <div class="col-4">
            <nav class="navbar navbar-expand-sm bg-light">

                <div class="container-fluid">
                  <!-- Links -->
                  <ul class="navbar-nav">
                    <li class="nav-item">
                      <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Services</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Clients</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">contacts</a>
                      </li>
                  </ul>
                </div>
              
              </nav>
        </div>
        <div class="col-2">
            <button class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#myModal">Login</button>
            <div class="modal" id="myModal">
                <div class="modal-dialog">
                  <div class="modal-content">
              
                    <!-- Modal Header -->
                    <div class="modal-header">
                      <h4 class="modal-title">Please login</h4>
                      <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
                    </div>
              
                    <!-- Modal body -->
                    <div class="modal-body">
                      <form action=""  class = "text-start">
                        Username
                        <input type="text" class="form-control">
                        password
                        <input type="password" class="form-control">
                      </form>
                    </div>
              
                    <!-- Modal footer -->
                    <div class="modal-footer">
                        <button type = "submit" class = "btn btn-success">Submit</button>
                      <button type="button" class="btn btn-danger" data-bs-dismiss="modal">Close</button>
                    </div>
              
                  </div>
                </div>
              </div>
        </div>
        <div class="col-2">
            <input type="text" placeholder="search" class="form-control">
        </div>
        <div class="col-2">
            <button type="submit" class="btn btn-primary">Submit</button>
        </div>
    </div>
    <div id="demo" class="carousel slide" data-bs-ride="carousel">

        <!-- Indicators/dots -->
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
          <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
          <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
        </div>
      
        <!-- The slideshow/carousel -->
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://www.w3schools.com/bootstrap5/la.jpg" height = "700" alt="Los Angeles" class="d-block w-100">
          </div>
          <div class="carousel-item">
            <img src="https://www.w3schools.com/bootstrap5/chicago.jpg" height = "700" alt="Chicago" class="d-block w-100">
          </div>
          <div class="carousel-item">
            <img src="https://www.w3schools.com/bootstrap5/ny.jpg" height = "700" alt="New York" class="d-block w-100">
          </div>
        </div>
      
        <!-- Left and right controls/icons -->
        <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
          <span class="carousel-control-prev-icon"></span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
          <span class="carousel-control-next-icon"></span>
        </button>
      </div>
      <div class = 'row mt-3'>
        <div class = "col-6" >
            <img width = 100% src="data:image/jpeg;base64,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" alt="">
        </div>
        <div class = "col-6  border border-dark text-Centre">
            <h1 class = "text-center text-primary" >Registration Form</h1>
            <form action="">
                <div class="mb-3 mt-3">
                    <label for="name" class="form-label">Name:</label>
                    <input type="text" class="form-control" id="text" placeholder="Enter name" name="name">
                  </div>
                <div class="mb-3 mt-3">
                  <label for="email" class="form-label">Email:</label>
                  <input type="email" class="form-control" id="email" placeholder="Enter email" name="email">
                </div>
                <div class="mb-3">
                  <label for="pwd" class="form-label">Password:</label>
                  <input type="password" class="form-control" id="pwd" placeholder="Enter password" name="pswd">
                </div>
                <div class="mb-3 mt-3">
                    <label for="city" class="form-label">city:</label>
                    <input type="text" class="form-control" id="city" placeholder="Enter city" name="city">
                  </div>
                <div>
                    <label for="State" class="form-label">State:</label>
                    <select class="form-select" aria-label="Default select example">
                        <option selected>Open this select menu</option>
                        <option value="1">One</option>
                        <option value="2">Two</option>
                        <option value="3">Three</option>
                      </select>
                </div>
                <br>
                <button type="submit" class="btn btn-primary">Submit</button>
                <br>
              </form>
        </div>
      </div>
      <div class="container mt-3" >            
        <table class="table table-striped table-hover table-bordered" width = 100% >
          <thead>
            <tr class = "table-primary">
              <th>S.no</th>
              <th>Reg.no</th>
              <th>name of the participant</th>
              <th>collaborative activity</th>
              <th>collaborating agency</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1</td>
              <td>UR16AE011</td>
              <td>ANIT ANU JOHN</td>
              <td>Product Design and Analysis</td>
              <td>CADD Centre</td>
            </tr>
            <tr>
                <td>2</td>
                <td>UR16AE011</td>
                <td>ANIT ANU JOHN</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <td>3</td>
                <td>UR16AE011</td>
                <td>ANIT ANU JOHN</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <td>4</td>
                <td>UR16AE011</td>
                <td>ANIT ANU JOHN</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <td>5</td>
                <td>UR16AE011</td>
                <td>ANIT ANU JOHN</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <td>6</td>
                <td>UR16AE011</td>
                <td>ANIT ANU JOHN</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <td>7</td>
                <td>UR16AE011</td>
                <td>ANIT ANU JOHN</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
              <tr>
                <td>8</td>
                <td>UR16AE011</td>
                <td>ANIT ANU JOHN</td>
                <td>Product Design and Analysis</td>
                <td>CADD Centre</td>
              </tr>
          </tbody>
        </table>
      </div>
    
</body>

</html>
