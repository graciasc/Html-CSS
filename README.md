# Html-CSS

<Doctype html>
    <html lang ="en">
        
        <head>
                <title> Gracias Website</title>
                <link rel ="stylesheet" href="GstyleA.css">

        </head>

        <body>
            <nav>
                <ul class= "firstTopNav"  id = "ham-menu-click">
                    
                    <li> <a href = "#home">Home</a></li>
                    <li><a href = "#news">News</a></li>
                    <li>   <a href = "#contact">Contact</a></li>
                    <li><a href = "#About">About</a> </li>
                    
                     <li class = "firstTopNav-right"><a href = "#Sign Up">Sign Up</a></li>
                     <li class = "firstTopNav-right"><a href = "#">Sign In</a></li>
                     <li class = "hamburger-Menu"><a href ="javascript:void(0);"
                        onclick ="hamOnClick">&#9776;</a></li>
                </ul>
            </nav>

            <div class= "container" id= "section-1-gradient"> 
            <div = class="row">
                <div class = "leftSide-col">
                    <div class ="leftSide-col" >
                        <h1 class ="firstCol">Developers</h1>
                        <h1 class= "secondCol"> by Gracias Claude</h1>
                    </div>
                    <form>
                        <div class = "leftSide-col">
                            <h2>Username</h2>
                            <input class = "inputbox" name="username" type="text" 
                            placeholder="Username">
                            <h2>Password</h2>
                            <input class = "inputbox" name="password" type="text" 
                            placeholder="Password">
                            
                        </div>
                    </form>
                </div>

                <div class = "col-6">
                    <div class= rightSide-col>
                        <div class = "videoContainer">
                            <iframe width="560" height="315" src="https://www.youtube.com/embed/ASArOYTKwW4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                    </div>

                </div>
            </div>


            <script>
                function hamOnClick() {
                    var a = document.getElementById("ham-menu-click");
                    if (a.className === firstTopNav ) {
                    a.className +="responsive";
                    /*change firstTopNav to firstTopNav responsive*/
                    }
                    else {
                        a.className = "firstTopNav";
                    }

                }
            </script>
        </body>

        </html>
