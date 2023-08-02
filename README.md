<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="mystylesport.css">
    <script src="https://kit.fontawesome.com/255e18cf2d.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <h2 class="logo"><span style="color: #ff004f;">T</span>homas.</h2>
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">services</a></li>
                    <li><a href="#portfolio">portfolio</a></li>
                    <li><a href="#contact">contact</a></li>
                    <i class="fa-solid fa-xmark" onclick="closemenu()"></i>
                </ul>
                <i class="fa-solid fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text">
                <p>Web/App Development</p>
                <h1>Hi, I'm <span>Ani</span><br> Thomas From Nigeria</h1>
            </div>
        </div>
    </div>
                                     <!------about--------->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="IMG_40.JPG" alt="">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <p>I am a front and back-end web Developer. 
                        i can provide clean code and pixel perfect designer. 
                        i also make the website more and more interactive with web animations.
                        i can provide clean code and pixel perfect designer.
                        i also make the website more and more interactive with web animations. 
                        A responsive design makes your website accessible to all users,
                         regardless of their device.</p>

                         <div class="tab-titles">
                            <p class="tab-links Active-link" onclick="opentab('skills')">Skills</p>
                            <p class="tab-links" onclick="opentab('experience')">Experience</p>
                            <p class="tab-links" onclick="opentab('education')">Education</p>
                         </div>
                         <div class="tab-contents Active-tab" id="skills">
                            <ul>
                                <li><span>UI/UX<br></span>Designing web/App interfaces</li>
                                <li><span>Web Development<br></span>Web App Development</li>
                                <li><span>App Development<br></span>Loading..............</li>
                            </ul>
                         </div>
                         <div class="tab-contents" id="experience">
                            <ul>
                                <li><span>2023<br></span>Loading..............</li>
                                <li><span>2023<br></span>Loading..............</li>
                                <li><span>2023<br></span>Web/App Development Training At Techocraft Academy</li>
                            </ul>
                         </div>
                         <div class="tab-contents" id="education">
                            <ul>
                                <li><span>2023<br></span>Loading..............</li>
                                <li><span>2023<br></span>Loading..............</li>
                                <li><span>2023<br></span>Web/App Development Training At Techocraft Academy</li>
                            </ul>
                         </div>
                </div>
            </div>
        </div>
    </div>
                             <!---  -------services----------  --->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                    <i class="fa-solid fa-code"></i>
                    <h2>Wep Development</h2>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                        Harum odio magni quisquam iusto hic impedit?</p>
                        <a href="#">Learn More</a>
                </div>
                <div>
                    <i class="fa-sharp fa-solid fa-crop"></i>
                    <h2>UX/UI</h2>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                        Harum odio magni quisquam iusto hic impedit?</p>
                        <a href="#">Learn More</a>
                </div>
                <div>
                    <i class="fa-brands fa-app-store-ios"></i>
                    <h2>App Development</h2>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
                        Harum odio magni quisquam iusto hic impedit?</p>
                        <a href="#">Learn More</a>
                </div>
            </div>
        </div>
    </div>
                             <!----- -------------portfolio----------- ------->
    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="IMG_4182.JPG">
                    <div class="layer">
                        <h3>Business Websites</h3>
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                        Alias fugit voluptate nisi rem!</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="IMG_4182.JPG">
                    <div class="layer">
                        <h3>Web App</h3>
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                        Alias fugit voluptate nisi rem!</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="IMG_4182.JPG">
                    <div class="layer">
                        <h3> Online Shooping App</h3>
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                        Alias fugit voluptate nisi rem!</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="btn">see More</a>
        </div>
    </div>
                                  <!------ ------contact--------- ------>
    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fa-solid fa-paper-plane"></i>anithomas003@gmail.com</p>
                    <p><i class="fa-solid fa-square-phone"></i>07045864484</p>
                    <div class="social-icons">
                        <a href=""><i class="fa-brands fa-facebook"></i></a>
                        <a href=""><i class="fa-brands fa-twitter-square"></i></a>
                        <a href=""><i class="fa-brands fa-instagram"></i></a>
                        <a href=""><i class="fa-brands fa-whatsapp"></i></a>
                    </div>
                    <a href="EarlyDecision.pdf" download class="btn btn2">Download Cv</a>
                </div>
                <div class="contact-right">
                    <form action="" name="submit-to-google-sheet">
                        <input type="text" name="Name" placeholder="Your Name" required>
                        <input type="email" name="Email" id="" placeholder="Your Email" required>
                        <textarea name="Masssage" rows="10" placeholder="Your Massage"></textarea>
                        <button type="submit" class="btn btn2">Submit</button>
                    </form>
                    <span id="msg"></span>
                </div>
            </div>
        </div>
        <footer> 
        <div class="copyright">
            <p>Mottor:Foreward Ever <i class="fa-solid fa-heart"></i></p>
        </div>
        <div class="icon-top">
            <a href="#header"><i class="fa-sharp fa-solid fa-arrow-up"></i></a>
        </div>
    </div>
 </footer>
 

    <script>

        let tablinks = document.getElementsByClassName('tab-links');
        let tabcontents = document.getElementsByClassName('tab-contents');
        
        function opentab(tabname) {
            for(tablink of tablinks){
                tablink.classList.remove('Active-link');
            }
            for(tabcontent of tabcontents){
                tabcontent.classList.remove('Active-tab');
            }
            event.currentTarget.classList.add('Active-link');
            document.getElementById(tabname).classList.add('Active-tab');
            
        }


    </script>
    
    <script>

        const sidemenu = document.querySelector('#sidemenu');
        function openmenu(){
            sidemenu.style.right = "0"
        };
        function closemenu(){
            sidemenu.style.right = "-200px"
        };


    </script>
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbyKn0rlIlS6cCf_UiZoS3NOV0d1pITT3IV3FrZpz9stDC7bgwLMG5i21j0lNr-SXifw/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById('msg')
      
        form.addEventListener('submit', e => {
          e.preventDefault()
          fetch(scriptURL, { method: 'POST', body: new FormData(form)})
            .then(response => {
                msg.innerHTML = 'massaga submit successfully'
                setTimeout(function(){
                    msg.innerHTML = ''
                },5000)
                form.reset();
            }
            .catch(error => console.error('Error!', error.message))
        })
      </script>
    
</body>
</html>
