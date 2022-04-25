# pet-salon-ch28
This is the pet salon version of the cohort 28
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <link rel="stylesheet" href="css/main.css">
    <title>The Fashion Pet</title>
</head>
<body>
    <header class="site-header">
        <h1>The Fashion Pet</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="services.html">Services</a>
            <a href="register.html">Register</a>
        </nav>
    </header>

    <main>

        <div class="form-container container">
            <h2>Register a new pet</h2>
            <div>
                <input class="form-control" type="text" id="txtName" placeholder="Enter the name">
            </div>
            <div>
                <input class="form-control"type="number" id="txtAge" placeholder="Enter the age">
            </div>
            <div >
                <input 
                class="form-control"
                type="text" id="txtGender" placeholder="Enter the gender">
            </div>
            <div >
                <input type="text" class="form-control" id="txtBreed" placeholder="Enter the Breed">
            </div>
            <div >
                <select class="form-control" id="selService">
                    <option value="nails cut">Nails cut</option>
                    <option value="shower">Shower</option>
                    <option value="grooming">Grooming</option>
                </select>
            </div>
            <div>
                <input class="form-control" type="text" id="txtOwner" placeholder="Enter the Owner's name">
            </div>
            <div >
                <input class="form-control" type="tel" id="txtTel" placeholder="Enter the Contact Phone">
            </div>
            <button onclick="register();" class="btn btn-primary">Register</button>
        </div>

        <div class="container" id="pets">
            <!-- display the names of the pets using
            <li> tag 
            -->
        </div>
    </main>
    
   
    <script src="scripts/display.js"></script>
    <script src="scripts/register.js"></script>

</body>
</html>
