

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'poppins', sans-serif;
    scroll-behavior: smooth;
}

body {
    color: white;
    background-color: black;
}

/*navbar*/

.header {Mehedi Hasan
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 20px 10%;
    background: #252525;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
    overflow: hidden;
    
}

.logo {
    position: relative;
    font-size: 25px;
    color: #fff;
    text-decoration: none;
    font-weight: 600;
    cursor: default;
    letter-spacing: 0px;
    opacity: 0;
    font-family: Moirai One;
    animation: slideRight 1s ease forwards;
}

.navbar a {
    display: inline-block;
    font-size: 25px;
    color: #fff;
    text-decoration: none;
    font-weight: 500;
    margin-left: 35px;
    transition: .3s;
    opacity: 0;
    animation: slideUP .5s ease forwards;
    animation-delay: calc(.2s * var(--i));
}

.navbar a:hover {
    color: #0ef;
    text-decoration: underline;
}

/*home*/

.home {
    position: relative;
    width: 100%;
    justify-content: space-between;
    min-height: 100vh;
    background-color: black;
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    padding: 70px 10% 0;
}

.home-content {
    max-width: 600px;
}

.home-content h1 {
    font-size: 56px;
    font-weight: 700;
    margin: -3px 0;
    letter-spacing: 5px;
    padding-top: 10px;
    padding-bottom: 10px;
    opacity: 0;
    animation: slideBottom 1s ease forwards;
    animation-delay: 1s;
}

.home-content h3 {
    font-size: 32px;
    font-weight: 700;
    opacity: 0;
    animation: slideBottom 1s ease forwards;
    animation-delay: .7s;
}

.home-content h4 {
    font-size: 32px;
    font-weight: 700;
    opacity: 0;
    animation: slideTop 1s ease forwards;
    animation-delay: calc(.2s * var(--i));
}

.home-content h4 span {
    color: #0ef;
    font-size: 32px;
    font-weight: 700;
}

.home-content h4:nth-of-type(2) {
    margin-bottom: 30px;

}

.home-sci a {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 40px;
    height: 40px;
    background: transparent;
    border: 2px solid #0ef;
    border-radius: 50%;
    font-size: 20px;
    color: #0ef;
    text-decoration: none;
    margin: 30px 15px 30px 0;
    opacity: 0;
    animation: slideTop 1s ease forwards;
    animation-delay: calc(.2s * var(--i));
}

.home-sci a:hover {
    background: #0ef;
    color: #000;
    box-shadow: 0 0 20px #0ef;
}

.btn-box {
    display: inline-block;
    padding: 12px 28px;
    background: #0ef;
    border-radius: 40px;
    font-size: 15px;
    text-align: center;
    color: #081b29;
    letter-spacing: 1px;
    text-decoration: none;
    font-weight: 600;
    opacity: 0;
    animation: slideTop .5s ease forwards;
    animation-delay: calc(.2s * var(--i));
}

.btn-box:hover {
    box-shadow: 0 0 5px cyan, 0 0 25px cyan, 0 0 50pc cyan, 0 0 100px cyan, 0 0 200px cyan;
}

.img {
    display: inline-block;
    left: 55%;
    bottom: 15%;
    margin-right: 5%;
    padding: 0;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    position: absolute;
    opacity: 0;
    animation: slideUP 1s ease forwards;
    animation-delay: 1s;
}

.responsive {
    width: 100%;
    height: auto;
    border-top-left-radius: 251px;
    border-top-right-radius: 251px;
    border-bottom-left-radius: 251px;
    border-bottom-right-radius: 251px;
}

/*about*/

.about {
    background-color: black;
    display: grid;
    grid-template-columns: repeat(2, .5fr);
    /*align-items: center;*/
    /*gap: 1.5rem;*/
    width: 100%;
    justify-content: space-between;
    min-height: 100vh;
    padding: 70px 5% 0;
}

.about-img {
    display: inline-block;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    padding-right: 10%;
    margin-top: 2.5%;
    /*margin-top: 7.5%;*/
    opacity: 1;
}

.abt-res {
    width: 100%;
    height: auto;
    max-width: 492px;
    max-height: 492px;
    border-radius: 90px;
    /*box-shadow: 0 0 5pc cyan, 0 0 5px cyan, 0 0 10px cyan;*/
    border: #0ef 5px solid;
}

.about-text {
    margin-right: 2%;
}

.about-text h2 {
    font-size: 60px;
    letter-spacing: 5px;
}

.about-text h2 span {
    color: #0ef;
}

.about-text p {
    color: aliceblue;
    font-size: 20px;
    line-height: 2;
    letter-spacing: 2px;
    margin-bottom: 4rem;
    text-align: justify;
    text-justify: inter-word;
}

.abtbtn-box {
    display: inline-block;
    padding: 12px 28px;
    background: #0ef;
    border-radius: 40px;
    font-size: 15px;
    text-align: center;
    color: #081b29;
    letter-spacing: 1px;
    text-decoration: none;
    font-weight: 600;
}

.abtbtn-box:hover {
    box-shadow: 0 0 5px cyan, 0 0 25px cyan, 0 0 50pc cyan, 0 0 100px cyan, 0 0 200px cyan;
}


/* Skills */
#Skills{
    background-color: #000;
}
.subtitle {
    text-align: center;
    font-size: 60px;
    padding-bottom: 10px;
    padding-top: 70px;
    
}

.subtitle span {
    color: #0ef;
}

.sec {
    display: flex;
    flex-wrap: wrap;
    padding-bottom: 0px;
}

.container1 {
    width: 600px;
    max-height: 500px;
    padding: 10px;
    margin-left: 100px;
}
.container2 {
    width: 600px;
    max-height: 500px;
    padding: 10px;
    margin-left: 100px;
}

.heading1 {
    text-align: center;
    text-decoration: underline;
    text-underline-offset: 5px;
    text-decoration-thickness: 5px;
    margin-bottom: 0px;
}

.bar {
    font-size: 23px;
}

.Technical-bars .bar {
    margin-top: 40px 0;
    padding: 5px;
}

.Technical-bars .bar:first-child {
    margin-top: 0;
}

.Technical-bars .bar:last-child {
    margin-bottom: 0;
}

.Technical-bars .bar .info {
    margin-bottom: 5px;
}

.Technical-bars .bar .info span {
    font-size: 17px;
    font-weight: 500;
    animation: showText 0.5s 1s linear forwards;
    opacity: 0;
}

.Technical-bars .bar .progress-line {
    position: relative;
    border-radius: 10px;
    width: 100%;
    height: 5px;
    background-color: #000;
    animation: animate 1s cubic-bezier(1, 0, 0.5, 1) forwards;
    transform: scaleX(0);
    transform-origin: left;
}

.Technical-bars .bar .progress-line span {
    height: 100%;
    background-color: #0ef;
    position: absolute;
    border-radius: 10px;
    animation: animate 1s 1s cubic-bezier(1, 0, 0.5, 1) forwards;
    transform: scaleX(0);
    transform-origin: left;
}

.progress-line.html span {
    width: 80%;
}

.progress-line.css span {
    width: 75%;
}

.progress-line.python span {
    width: 70%;
}

.progress-line.java span {
    width: 50%;
}

.progress-line.cpls span {
    width: 50%;
}

.progress-line span::after {
    position: absolute;
    padding: 1px 8px;
    background-color: #000;
    color: #fff;
    font-size: 12px;
    border-radius: 3px;
    top: -28px;
    right: -20px;
    animation: showText 0.5s 1.5s linear forwards;
    opacity: 0;
}

.progress-line.html span::after {
    content: "80%";
}

.progress-line.css span::after {
    content: "75%";
}

.progress-line.python span::after {
    content: "70%";
}

.progress-line.java span::after {
    content: "50%";
}

.progress-line.cpls span::after {
    content: "50%";
}

.progress-line span::before {
    content: "";
    position: absolute;
    width: 0;
    height: 0;
    border: 7px solid transparent;
    border-bottom-width: 0px;
    border-right-width: 0px;
    border-top-color: #000;
    top: -10px;
    right: 0;
    animation: showText 0.5s 1.5s linear forwards;
    opacity: 0;
}

.radial-bars {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    align-items: flex-start;
}

.radial-bars .radial-bar {
    width: 50%;
    height: 170px;
    margin-bottom: 10px;
    position: relative;
}

.radial-bars .radial-bar svg {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%) rotate(-90deg);
    width: 120px;
    height: 160px;
}

.radial-bars .radial-bar .progress-bar {
    stroke-width: 10;
    stop-color: black;
    fill: transparent;
    stroke-dasharray: 502;
    stroke-dashoffset: 502;
    stroke-linecap: round;
    animation: animate-bar 1s linear forwards;
}

.path {
    stroke-width: 10;
    stroke: #0ef;
    fill: transparent;
    stroke-dasharray: 502;
    stroke-dashoffset: 502;
    stroke-linecap: round;
}

.path.path-1 {
    animation: animate-path1 1s 1s linear forwards;
}

.path.path-2 {
    animation: animate-path2 1s 1s linear forwards;
}

.path.path-3 {
    animation: animate-path3 1s 1s linear forwards;
}

.path.path-4 {
    animation: animate-path4 1s 1s linear forwards;
}

.radial-bar .percentage {
    position: absolute;
    align-items: center;
    top: 50%;
    left: 45%;
    transform: translate(-50%, -50%);
    font-size: 17px;
    font-weight: 500;
    animation: showText 0.5s 1s linear forwards;
    opacity: 0;
}

.radial-bar .text {
    width: 100%;
    position: absolute;
    text-align: center;
    left: 15%;
    bottom: 5px;
    transform: translateX(-50px);
    font-size: 17px;
    font-weight: 500;
    animation: showText 0.5s 1s linear forwards;
    opacity: 0;
}

/*projects*/
#Projects{
    background-color: #000;
}
.main-text {
    padding-top: 50px;
    margin-top: 10px;
    padding-bottom: 130px;
}

.main-text h2 {
    font-size: 60px;
    line-height: 1;
    text-align: center;
    padding: 50px;
    padding-bottom: 110px;
}

.main-text h2 span {
    color: #0ef;
}

.serv-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(259px, auto));
    align-items: center;
    justify-content: space-around;
}

.row {
    position: relative;
    border-radius: 8px;
    cursor: pointer;
    padding: 0px;
    overflow: hidden;
}

.row img {
    width: 100%;
    max-width: 300px;
    max-height: 300px;
    border-radius: 15px;
    display: block;
    transition: transform 0.5s;
    padding: 10px;
}

.layer {
    width: 100%;
    max-width: 300px;
    max-height: 300px;
    height: 0;
    opacity: 0;
    background: linear-gradient(rgba(255, 255, 255, 0.5), #0ef);
    position: absolute;
    border-radius: 8px;
    left: 0;
    bottom: 0;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 40px;
    transition: height 0.5s;
}

.layer h5 {
    color: #000;
    font-size: 20px;
    font-weight: 600;
    margin-bottom: 15px;
}

.layer p {
    color: black;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.8;
    text-align: justify;
}

.layer i {
    color: #0ef;
    margin-top: 20px;
    font-size: 20px;
    background: #000;
    width: 60px;
    height: 60px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
}

.row:hover img {
    transform: scale(1.01);
}

.row:hover .layer {
    height: 100%;
    opacity: 1;
}

/* Service*/

#Services{
    background-color: #000;
}

.sub-title {
    text-align: center;
    font-size: 60px;
    padding-top: 0px;
    padding-bottom: 70px;
}

.sub-title span {
    color: #0ef;
}

.prj-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(259px, 1fr));
    grid-gap: 40px;
    margin-top: 50px;
}

.prj-list div {
    background-color: transparent;
    padding: 40px;
    font-size: 13px;
    font-weight: 13px;
    border-right: 10px;
    border-radius: 20px;
    transition: background 0.5s, transform 0.5s;
    /*box-shadow: 1px 1px 20px #012290f7, 1px 1px 40px #0053b8f7;*/
    border: #0ef 5px solid;
}

.container {
    padding: 50px;

}

.prj-list div i {
    font-size: 50px;
    margin-bottom: 30px;
}

.prj-list div h2 {
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 15px;
}

.prj-list div a {
    text-decoration: none;
    color: #000;
    font-size: 12px;
    margin-top: 20px;
    display: inline-block;
}

.read {
    display: inline-block;
    padding: 12px 20px;
    background: #0ef;
    border-radius: 40px;
    font-size: 16px;
    color: #081b29;
    letter-spacing: 1px;
    text-decoration: none;
    font-weight: 600;
    opacity: 0;
    animation: slideTop 1s ease forwards;
    animation-delay: 1s;
}

.read:hover {
    box-shadow: 0 0 5px cyan, 0 0 25px cyan, 0 0 50pc cyan, 0 0 100px cyan, 0 0 200px cyan;
}

.prj-list div:hover {
    transform: translateY(-2px);
}


/*contacts*/

.contacts {
    display: grid;
    /*grid-template-columns: repeat (2, 1fr);*/
    align-items: center;
    gap: 3rem;
    padding: 40px;
    padding-top: 70px;
    justify-content: center;
    background-color: #000;
}

.contact-text {
    align-content: center;
}

.contact-text h2 {
    font-size: 60px;
    line-height: normal;
    text-align: center;

}

.contact-text h2 span {
    color: #0ef;
}

.contact-text h4 {
    margin: 15px 0;
    color: rgb(228, 228, 228);
    font-size: 20px;
    font-weight: 600;
}

/*.contact-text p{
    color: rgb(177, 177, 177);
    font-size: 20px;
    line-height: 30px;
    margin-bottom: 2rem;
}*/
.contact-list {
    margin-bottom: 3rem;
}

.contact-list li {
    margin-bottom: 10px;
    display: block;
    margin-bottom: 10px;
    letter-spacing: 2px;
}

.contact-list i {
    display: inline-block;
    color: #0ef;
    font-size: 20px;
    font-weight: 600;
    transition: all .40s ease;
    padding: 10px;
}


.contact-icons i {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 40px;
    height: 40px;
    background: transparent;
    border: 2px solid #0ef;
    border-radius: 50%;
    font-size: 20px;
    color: #0ef;
    text-decoration: none;
    margin: 0px 15px 0px 0;
    opacity: 1;
}

.contact-icons i:hover {
    background: #0ef;
    color: #000;
    box-shadow: 0 0 20px #0ef;
}

.last-text p{
    width: 100%;
    text-align: center;
    padding: 25px;
    background: black;
    font-weight: 300;
    margin-top: 0px;
}
.top{
    position: fixed;
    bottom: 2.1rem;
    left: 1rem;
    display: flex;
    opacity: 0;
    transition: all .4s;
}

.top.active{
    bottom: 32px;
    pointer-events: auto;
    opacity: 1;
}

.top i{
    color: black;
    background: #0ef;
    font-size: 20px;
    padding: 10px;
    border-radius: 0.5rem;
}

.top i:hover {
    box-shadow: 0 0 5px cyan,
    0 0 25px cyan, 0 0 50px cyan,0 0 200px cyan;
}



@keyframes animate-path1 {
    100% {
        stroke-dashoffset: 180;
    }
}

@keyframes animate-path2 {
    100% {
        stroke-dashoffset: 140;
    }
}

@keyframes animate-path3 {
    100% {
        stroke-dashoffset: 90;
    }
}

@keyframes animate-path4 {
    100% {
        stroke-dashoffset: 50;
    }
}

@keyframes animate-bar {
    100% {
        stroke-dashoffset: -1;
    }
}

@keyframes showText {
    100% {
        opacity: 1;
    }
}

@keyframes animate {

    100% {
        transform: scaleX(1);
    }
}

@keyframes slideRight {
    0% {
        transform: translateX(-100px);
        opacity: 0;
    }

    100% {
        transform: translateX(0px);
        opacity: 1;
    }
}

@keyframes slideTop {
    0% {
        transform: translateX(100px);
        opacity: 0;
    }

    100% {
        transform: translateX(0px);
        opacity: 1;
    }
}

@keyframes slideBottom {
    0% {
        transform: translateX(-100px);
        opacity: 0;
    }

    100% {
        transform: translateX(0px);
        opacity: 1;
    }
}

@keyframes slideUP {
    0% {
        transform: translateY(50px);
        opacity: 0;
    }

    100% {
        transform: translateY(0px);
        opacity: 1;
    }
}

@media (max-width: 900px) and (min-width: 700px) {
    .header{
        display:block;
    }
    .logo {
        position: relative;
        font-size: 30px;
        font-weight: 500;
        text-align: center;
    }
    .logo::after{
        content: "\a";
        white-space: pre;
    }
    .navbar a {
        font-size: 25px;
        font-weight: 200;
        margin-left: 0px;
        padding: 10px 10px 0 0;
    }
    .navbar a::after{
        content: "\a";
        white-space: pre;
    }
    
}

@media (max-width: 700px) and (min-width: 400px) {
    *{
        overflow-x: hidden;
        overflow-y: inherit;
    }
    /*navbar*/
    .header{
        display:block;
        
    }
    .logo {
        position: relative;
        font-size: 20px;
        font-weight: 500;
        text-align: center;
    }
    .logo::after{
        content: "\a";
        white-space: pre;
    }
    .navbar a {
        font-size: 15px;
        font-weight: 200;
        margin-left: 0px;
        padding: 10px 10px 0 0;
    }
    .navbar a::after{
        content: "\a";
        white-space: pre;
    }

    /*home*/
    .home{
        align-items: normal;
        padding-top: 40%;
        padding-bottom: 0;
    }
    .home-content h1 {
        font-size: 40px;
        font-weight: 600;
    }
    
    .home-content h3 {
        font-size: 30px;
        font-weight: 300;
    }
    
    .home-content h4 {
        font-size: 18px;
        font-weight: 200;
    }
    
    .home-content h4 span {
        font-size: 18px;
        font-weight: 200;
    }
    .img{
        max-width: 400px;
        position: relative;
        left: -10%;
        top: 2%;
        padding-bottom: 30px;
        padding-left: 0;
        margin-left: 0;
    }
    .btn-box:hover {
        box-shadow: 0 0 5px cyan, 0 0 10px cyan, 0 0 15pc cyan, 0 0 20px cyan, 0 0 25px cyan;
    }
    /*about*/
    .about{
        padding-bottom: 20px;
        min-height: auto;
    }
    .about-text h2 {
        font-size: 30px;
        letter-spacing: 5px;
    }
    
    .about-text p {
        font-size: 15px;
        line-height: normal;
        letter-spacing: 1px;
        margin-bottom: 4rem;
        text-align: left;
    }
    .abtbtn-box:hover {
        box-shadow: 0 0 5px cyan, 0 0 10px cyan, 0 0 15pc cyan, 0 0 20px cyan, 0 0 25px cyan;
    }

    /*skills*/
    .subtitle{
        font-size: 50px;
        text-align: center;
    }
    .container1 {
        width: 600px;
        max-height: 500px;
        padding: 20px;
        margin-left: 50px;
    }
    .container2 {
        width: 600px;
        max-height: 500px;
        padding: 10px;
        margin-left: 0px;
    }
    .bar .info .addhtml::before{
        content: "90%";
    }
    .bar .info .addcss::before{
        content: "80%";
    }
    .bar .info .addpy::before{
        content: "75%";
    }
    .bar .info .addjava::before{
        content: "50%";
    }
    .bar .info .addc::before{
        content: "50%";
    }

    /*project*/
    .main-text {
        padding-top: 20px;
        margin-top: 10px;
        padding-bottom: 50px;
    }
    .main-text h2 {
        font-size: 50px;
        padding-bottom: 15px;
    }
    .layer p {
        line-height: normal;
    }
    /*service*/
    .sub-title {
        font-size: 50px;
        padding-bottom: 50px;
    }
    .prj-list div{
        padding: 20px;
    }
    /*contact*/
    .contacts h2{
        font-size: 50px;
    }
    .contact-list i{
        font-size: 15px;
        padding: 5px 5px 0 0;
    }
    
    .top{
        position: fixed;
        bottom: 2rem;
        left: 1rem;
        display: inline-flex;
        align-items: center;
        justify-content: center;
        text-decoration: none;
        opacity: 0;
        transition: all .4s;
    }
    
}

@media (max-width: 400px) {
    *{
        overflow-x: hidden;
    }
    .header{
        display:block;
    }
    .logo {
        position: relative;
        font-size: 20px;
        font-weight: 500;
        text-align: center;
    }
    .logo::after{
        content: "\a";
        white-space: pre;
    }
    .navbar a {
        font-size: 13px;
        font-weight: 200;
        margin-left: 0px;
        padding: 10px 4px 0 0;
    }
    .navbar a::after{
        content: "\a";
        white-space: pre;
    }

    /*home*/
    .home{
        width: 100%;
        align-items: normal;
        padding-top: 40%;
        padding-bottom: 0;
    }
    .home-content h1 {
        font-size: 30px;
        font-weight: 600;
    }
    
    .home-content h3 {
        font-size: 20px;
        font-weight: 300;
    }
    
    .home-content h4 {
        font-size: 15px;
        font-weight: 200;
    }
    
    .home-content h4 span {
        font-size: 15px;
        font-weight: 200;
    }
    .btn-box:hover {
        box-shadow: 0 0 5px cyan, 0 0 10px cyan, 0 0 15pc cyan, 0 0 20px cyan, 0 0 25px cyan;
    }
    .img{
        max-width: 300px;
        position: relative;
        left: -10%;
        top: 2%;
        padding-bottom: 30px;
        padding-left: 0;
        margin-left: 0;
        margin-right: 0;
    }
    
    /*about*/
    .about{
        padding-bottom: 20px;
        min-height: auto;
    }
    .about-text h2 {
        font-size: 30px;
        letter-spacing: 5px;
    }
    
    .about-text p {
        font-size: 15px;
        line-height: normal;
        letter-spacing: 0px;
        margin-bottom: 4rem;
        text-align: left;
    }
    .abtbtn-box:hover {
        box-shadow: 0 0 5px cyan, 0 0 10px cyan, 0 0 15pc cyan, 0 0 20px cyan, 0 0 25px cyan;
    }

    /*skills*/
    .subtitle{
        font-size: 50px;
        text-align: center;
    }
    .container1 {
        width: 600px;
        max-height: 500px;
        padding: 20px;
        margin-left: 50px;
    }
    .container2 {
        width: 600px;
        max-height: 500px;
        padding: 10px;
        margin-left: 0px;
    }
    .radial-bar .text{
        left: 25%;
    }
    .bar .info .addhtml::before{
        content: "90%";
    }
    .bar .info .addcss::before{
        content: "80%";
    }
    .bar .info .addpy::before{
        content: "75%";
    }
    .bar .info .addjava::before{
        content: "50%";
    }
    .bar .info .addc::before{
        content: "50%";
    }

    /*project*/
    .main-text {
        padding-top: 20px;
        margin-top: 10px;
        padding-bottom: 50px;
    }
    .main-text h2 {
        font-size: 50px;
        padding-bottom: 15px;
    }
    .layer p {
        line-height: normal;
    }

    /*service*/
    .sub-title {
        font-size: 50px;
        padding-bottom: 50px;
    }

    /*contact*/
    .contacts h2{
        font-size: 50px;
         position: center;
    }
    .contact-list i{
        font-size: 13px;
        padding: 5px 5px 0 0;
        position: center;
    }
    
    .top{
        position: fixed;
        bottom: 2rem;
        left: 1rem;
        display: inline-flex;
        align-items: center;
        justify-content: center;
        text-decoration: none;
        opacity: 0;
        transition: all .4s;
    }
    .top i{
        color: #000;
    }
}
