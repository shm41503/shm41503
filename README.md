<div id="header" align="center">
  <img src="https://i.pinimg.com/564x/ea/6a/f2/ea6af2d4f6ab7bd239d7ef5b6871f0ab.jpg" width="100"/>
</div>
<!DOCTYPE html>

<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Gun Lee</title>
        <!--Bootstrap css-->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.4.1/font/bootstrap-icons.css">
        <!--Custome CSS RUle-->
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="container">
            <h1>SooHyun Moon's Profile</h1>
            <div class="TableofContents">
                <!--content list + link to parts of the page-->
                <h2><i class="bi bi-pin-angle"></i> Contents</h2>
                <ul>
                <li><a href="#personalinfo">Personal Information</a></li>
                <li><a href="#contactinfo">Contact Information</a></li>
                <li><a href="#tmi">Random Fact About Me</a></li>
                <li><a href="#interests">Interests</a></li>
                </ul>
            </div>
            <!--Personal information-->
            <div id="personalinfo" class="personalinfo">
                <h2><i class="bi bi-info-circle"></i> Personal Information</h2>
                <!--image using bootstrap classes and utilities-->
                <img src="photo.png" class="img-fluid rounded mx-auto d-block" />
                <ul class="py-2">
                    <li>Name: SooHyun Moon</li>
                    <li>Age: 19</li>
                    <li>University: Sungkyunkwan University (SKKU)</li>
                </ul>
            </div>
            <!--contactinfo-->
            <div id="contactinfo" class="contactinfo">
                <h2><i class="bi bi-mailbox2"></i> Contact Information</h2>
                <!--Use of table-->
                <!--links to the websites-->
                <!--Bootstrap color, rounded,-->
                <div class="dflex mb-2">
                    <table class = "bg-secondary rounded-2 table-bordered">
                        <tr>
                            <th>Platform</th>
                            <th>Email Address (username)</th>
                        </tr>
                        <tr>
                            <td><a href="https://www.google.com/">Google</a></td>
                            <td>gdlee412@gmail.com</td>
                        </tr>
                        <tr>
                            <td><a href="https://www.skku.edu/skku/index.do">SKKU</a></td>
                            <td>leegundaniel@g.skku.edu</td>
                        </tr>
                        <tr>
                            <td><a href="https://github.com/">GitHub</a></td>
                            <td>shm4153@g.skku.edu (<a href="https://github.com/shm41503">shm41503</a>)</td>
                        </tr>
                    </table>
                </div>
            </div>
            <!--TMI / facts-->
            <div id="tmi" class="tmi">
                <!--add padding in top and bottom-->
                <h2 class="pt-5 pb-3"><i class="bi bi-search"></i> Random Fact About Me</h2>
                <p>I currently have <strong>THREE</strong> pets, 2 dogs, and one cat!!</p>
            </div>
            <!--Interests-->
            <div id="tmi" class="tmi">
                <!--add padding in top and bottom-->
                <h2 class="pt-5 pb-3"><i class="bi bi-bookmark"></i> Interests</h2>
                <ul>
                    <li>Music</li>
                    <li>Sports</li>
                </ul>
            </div>
            <div id="end" class="end">
                <h2>Thank you!</h2>
                <p>Thank you so much for visiting my website. Hope you have a great day!!</p>
            </div>
            <!--Bootstrap JS-->
            <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous"></script>
        </div>
    </body>
</html>

<div class = "d-flex">
    <div class="flex-grow-1 bg-light rounded-2 p-2 me-1 w-50">
