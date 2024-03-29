<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css"/>

</head>
<body>
    <div class="scroll-up-btn">
        <i class="fas fa-angle-up"></i>
    </div>
    <nav class="navbar">
        <div class="max-width">
            <div class="logo"><a href="#">pt<span>santhoshkumar.</span></a></div>
            <ul class="menu">
                <li><a href="#home" class="menu-btn">Home</a></li>
                <li><a href="#about" class="menu-btn">About</a></li>
                <li><a href="#services" class="menu-btn">Services</a></li>
                <li><a href="#skills" class="menu-btn">Skills</a></li>
                <li><a href="#teams" class="menu-btn">Teams</a></li>
                <li><a href="#contact" class="menu-btn">Contact</a></li>
            </ul>
            <div class="menu-btn">
                <i class="fas fa-bars"></i>
            </div>
        </div>
    </nav>

    <!-- home section start -->
    <section class="home" id="home">
        <div class="max-width">
            <div class="home-content">
                <div class="text-1">Hi, my name is</div>
                <div class="text-2">Santhosh Kumar</div>
                <div class="text-3">And I'm a <span class="typing"></span></div>
                <a href="https://www.linkedin.com/in/ptsanthoshkumar/">Hire me</a>
            </div>
        </div>
    </section>

    <!-- about section start -->
    <section class="about" id="about">
        <div class="max-width">
            <h2 class="title">About me</h2>
            <div class="about-content">
                <div class="column left">
                    <img src="images/photo_2022-11-23_23-51-06.jpg" alt="">
                </div>
                <div class="column right">
                    <div class="text">I'm Santhosh and I'm a <span class="typing-2"></span></div>
                    <p>Hey there, I'm Santhosh—a tech enthusiast on a thrilling journey across the landscapes of machine learning, AI, and software development. My code is my canvas, where I bring ideas to life with finesse. Beyond the digital realm, I find joy in capturing life's moments through the lens, indulging in the art of photography and video editing. Drones, my skyward companions, elevate my creativity to new heights. With a passion for innovation and a diverse skill set, I'm on a mission to make waves in the tech and creative spheres.</p>
                    <a href="https://drive.google.com/uc?export=download&id=1GaWusAaFsUfwwyuTKpBqcBnkpqQ_dMLf">Download Resume</a>
                    <a href="https://drive.google.com/file/d/1GaWusAaFsUfwwyuTKpBqcBnkpqQ_dMLf/view?usp=sharing">View Resume</a>
                </div>
            </div>
        </div>
    </section>

    <!-- services section start -->
    <section class="services" id="services">
        <div class="max-width">
            <h2 class="title">My services</h2>
            <div class="serv-content">
                <div class="card">
                    <div class="box">
                        <i class="fas fa-code"></i>
                        <div class="text">Software Development</div>
                        <p class="touchh">Can code in various environments and adapt to each and every one of them</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <i class="fas fa-camera"></i>
                        <div class="text">Photography</div>
                        <p class="touchh">Photography as a hobby with drones and cameras</p>
                        <a class="butt" href="https://ptsanthoshkumar.my.canva.site/ptsanthoshkumar">Photography site</a>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <i class="fas fa-paint-brush"></i>
                        <div class="text">Edit videos</div>
                        <p class="touchh">Edit videos for social media and commercial purposes with Premiere Pro</p>
                    </div>
                </div>
               </div>
            </div>
        </div>
    </section>

    <!-- skills section start -->
    <section class="skills" id="skills">
        <div class="max-width">
            <h2 class="title">My skills</h2>
            <div class="skills-content">
                <div class="column left">
                    <div class="text">My creative skills & experiences.</div>
                    <p>
                        In the vast landscape of tech, I command proficiency in machine learning, AI, and software development, sculpting digital innovations with precision. My creative pursuits find expression in the captivating realms of photography and video editing, where each frame tells a unique story. Drones, my airborne companions, extend my creative reach. My versatile skill set fuels a passion for pushing the boundaries at the intersection of technology and artistic expression.</p>
                    <a href="https://sites.google.com/view/ptsanthoshkumar/hobbies">Read more</a>
                </div>
                <div class="column right">
                    <div class="bars">
                        <div class="info">
                            <span>Python</span>
                            <span>90%</span>
                        </div>
                        <div class="line html"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Java</span>
                            <span>60%</span>
                        </div>
                        <div class="line css"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>SQL</span>
                            <span>80%</span>
                        </div>
                        <div class="line js"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>C and C++</span>
                            <span>60%</span>
                        </div>
                        <div class="line php"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Cloud Tech (AWS)</span>
                            <span>80%</span>
                        </div>
                        <div class="line mysql"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- teams section start -->
    <section class="teams" id="teams">
        <div class="max-width">
            <h2 class="title">My Projects</h2>
            <div class="carousel owl-carousel">
                <div class="card">
                    <div class="box">
                        <img src="images/_b3194aec-6dfc-421f-8b4f-1d39b93433f2.jpeg" alt="">
                        <div class="text">Turbo Play</div>
                        <p class="touchh">A cloud based gaming service which makes large and compute intensive games available for all 💓</p>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/person-using-ai-tool-job.jpg" alt="">
                        <div class="text">Neural Nets</div>
                        <p>Neural Networks demonstrated with just mathematics and coding.</p>
                        <a href="https://github.com/ptsanthoshkumar/Neural-nets-no-packages" class="butt">GitHub</a>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/ai-cloud-concept-with-robot-arm.jpg" alt="">
                        <div class="text">Lung Cancer - CNN</div>
                        <p>Convolutional neural network for lung cancer prediction.</p>
                        <a href="https://github.com/ptsanthoshkumar/CNN-Lung-cancer" class="butt">GitHub</a>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/25758-1-stock-market-hd.png" alt="">
                        <div class="text">Stock prices - NN</div>
                        <p>Stock price prediction with neural networks.</p>
                        <a href="https://github.com/ptsanthoshkumar/stonksnn" class="butt">GitHub</a>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <img src="images/kidney.avif" alt="">
                        <div class="text">CKD Prediction</div>
                        <p>Kidney disease prediction with machine learning.</p>
                        <a href="https://github.com/ptsanthoshkumar/ckdprediction-mlt" class="butt">GitHub</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="contact" id="contact">
        <div class="max-width">
            <h2 class="title">Contact me</h2>
            <div class="contact-content">
                <div class="column left">
                    <div class="text">Get in Touch</div>
                    <div class="icons">
                        <div class="row">
                            <i class="fas fa-user"></i>
                            <div class="info">
                                <div class="head">Name</div>
                                <div class="sub-title">Santhosh Kumar P T</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-map-marker-alt"></i>
                            <div class="info">
                                <div class="head">Location</div>
                                <div class="sub-title">Chennai, India</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-envelope"></i>
                            <div class="info">
                                <div class="head">Email</div>
                                <div class="sub-title">ptsanthoshkumar24@gmail.com</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column right">
                    <div class="text">Message me</div>
                    <form name="submit-to-google-sheet" onsubmit="this.submit(); this.reset(); return false;">
                        <div class="fields">
                            <div class="field name">
                                <input type="text" name="Name" placeholder="Name" required>
                            </div>
                            <div class="field email">
                                <input type="email" name="email" placeholder="Email" required>
                            </div>
                        </div>
                        <div class="field">
                            <input type="text" name="subject" placeholder="Subject" required>
                        </div>
                        <div class="field textarea">
                            <textarea name="message" cols="30" rows="10" placeholder="Message.." required></textarea>
                        </div>
                        <div class="button-area">
                            <button type="submit">Send message</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>
    <footer>
        <span>Created By <a href="https://sites.google.com/view/ptsanthoshkumar">ptsanthoshkumar</a> | <span class="far fa-copyright"></span> 2024 All rights reserved.</span>
    </footer>
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbx9ya8hffXw_3eUvzRyxpycOgKLK9CmfLEMB-JmgDacmAT5IvUUa2yDjU-MyUeAh_0r/exec'
        const form = document.forms['submit-to-google-sheet']
      
        form.addEventListener('submit', e => {
          e.preventDefault()
          fetch(scriptURL, { method: 'POST', body: new FormData(form)})
            .then(response => console.log('Success!', response))
            .catch(error => console.error('Error!', error.message))
        })
      </script>
    <script src="script.js"></script>
</body>
</html>
