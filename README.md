# SandstoneWebpage
About Us code
## CSS
'''
/* Footer Changes */
.uncode-vc-social{
	text-align: center;
	/*margin-top: 60px !important;*/
	color: #0f6773 !important;
}
div.uncode_text_column{
	margin-top: 0px !important;
}
p.widget-title{
	margin-top: 7px;
}
.dpr-info-wrap{
 font-size: 17px !important;
}
.widget-title{
	font-weight: 500;
}
/* Posts and Publications */
.fontsize-338686{
	font-size:35px;
}
'''
## Custom CSS
'''
.about-us-headings{
    font-weight:500;
    font-size:28px !important;
}
.bio-images{
    padding:auto 5%;
    display: table-cell;
    vertical-align: middle;
    text-align: center;    
}
/*.bio-images:hover{*/
/*    cursor:pointer;*/
/*}*/

/*Bio Decriptions*/
.bio-name{
    color: #0f6773 !important;
    margin: 9px 0px 9px 0px;
    font-size:18px !important;
    font-family: 'Oxygen', sans-serif!important;
    font-weight:300;
    padding-top:7px;
    text-align: center;

}
.bio-title{
    color: #0f6773 !important;
    font-size: 12px !important;
    font-weight: 600;
    line-height: 1.4;
    font-family: 'SF-Pro-Display',Roboto,Sans-Serif;
    margin: 10px 0px;
    text-align: center;

}
#karenDesc,
#garyDesc,
#gregDesc, 
#ulrichDesc, 
#brianDesc, 
#debDesc, 
#daveDesc, 
#kyungjinDesc, 
#gabriellaDesc, 
#seanDesc,
#jonDesc, 
#claraDesc,
#angelaDesc,
#tifanyDesc,
#bhumikaDesc,
#shannonDesc,
#maggieDesc,
#jasonDesc{
  width: 100%;
  padding: 0 0 10px 0;
  text-align: center;
  background-color: white;
  display:none;
  font-size:16px;
  line-height:1.4;
  color:#323232;//here
}
.bio-col{
    padding:9px !important;
    text-align:center
}
.bio-col .fa-linkedin{
    color: #0f6773;/*gray color #8499a8*/
    margin-top:5px;
}
.about-us-headings{
    margin:0 !important;
}
.about-btn{
    font-family: 'Poppins', Poppins, 'Oxygen', sans-serif !important;
       background: white;
    border: 1px solid #8499a8;
    box-sizing: border-box;
    cursor: pointer;
    display: inline-block;
    font-size: 12px;
    line-height: 20px;
    padding: 0 15px; //7, 11
    position: relative;
    text-align: center;
    border-radius: 18px;
    border-color:#888888;//#8499a8;
    color: #888888;//#8499a8;
    font-weight:500;
}
.about-btn:hover{
    background: #0f6773;
        color: white;
        border-color:white;

}
.boardH1{
    padding-bottom:30px;
    padding-top: 50px;

}
'''

## HTML
'''
<script src="https://kit.fontawesome.com/5fc3d9e961.js" crossorigin="anonymous"></script>

<div class = "row bios-all">

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/08/GGA-headshot-SQUARE-for-SDx-website-IMG_4212.jpeg" width="516" height="516" >
<h3 class = "bio-name" >Gary Altman, PhD</h3>
<h4 class="bio-title">Chief Executive Officer</h4>
<div id="garyDesc">
Gary is an accomplished CEO, COO, VP and GM with more than 20-years’ experience in start-ups and global businesses including diagnostics, therapeutics, genomics, and life sciences. Gary's past positions include roles at Beckman Coulter, Human Longevity, and Sequoia Pharmaceuticals in addition to an expansive consulting career leading business and strategy initiatives for many small to mid-sized companies. Throughout his career, Gary has launched products, led turnarounds, expanded markets, raised Angel and Venture Capital, and managed budgets up to $250M.
<br>
<a href="https://www.linkedin.com/in/garygaltman/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myGary">About  <i class="fas fa-chevron-down"></i></button>
</div>


<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/05/Sommer_pic_lowres-e1591816256572.jpg" width="516" height="516" >
<h3 class = "bio-name" >Greg Sommer, PhD</h3>
<h4 class="bio-title">CoFounder and Executive Vice President</h4>
<div id="gregDesc">
Greg has over 15 years experience developing point-of-care diagnostic tools. Prior to cofounding Sandstone, he was a Senior Research Scientist at Sandia National Laboratories where he led R&D in point-of-care diagnostic technologies for biodefense and emergency preparedness applications. Greg is a co-inventor on over 20 issued patents, a co-author on 15 peer-reviewed publications, was named a 2015 Bay Area "40 Under 40", and earned his Mechanical Engineering degrees from Iowa State University and the University of Michigan.
<br>
<a href="https://www.linkedin.com/in/gregsommer1/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myGreg">About  <i class="fas fa-chevron-down"></i></button>
</div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/03/UlrichSchaff.jpg" width="516" height="516" >
<h3 class = "bio-name" >Ulrich Schaff, PhD</h3>
<h4 class="bio-title">CoFounder and Chief Technology Officer</h4>
<div id="ulrichDesc">
Ulrich leads design and development of Sandstone's new products from concept phase through validation and clinical trials. In addition, as a registered patent agent, he is responsible for managing and expanding Sandstone's IP portfolio. Prior to Sandstone, Ulrich was a Research Scientist at Sandia National Laboratories where he invented the SpinDx point-of-care diagnostic platform. Ulrich is an inventor on over 15 issued patents and earned his degrees in Biomedical Engineering from UC Berkeley, UC San Diego, and UC Davis.
<br>
<a href="https://www.linkedin.com/in/uschaff/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myUlrich">About  <i class="fas fa-chevron-down"></i></button>
 </div>
</div>
'''

'''
<div class = "row bios-all">

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/03/BrianAwabdy.jpg" width="516" height="516">
<h3 class = "bio-name" >Brian Awabdy</h3>
<h5 class ="bio-title">VP of Operations and Quality</h5>
<div id="brianDesc">
Brian is an experienced technical development and engineering leader, specializing in hands-on process and product development, continuous improvement, cross-functional project management, and engineering management. Prior to Sandstone, Brian held executive roles at Spirosure, CellScape, and Apieron where he managed a multi-year project to successfully commercialize and enhance the first biosensor-based Class II IVD medical device approved by the FDA. Brian earned his MS and BS degrees in Mechanical Engineering from UC Berkeley.
<br>
<a href="https://www.linkedin.com/in/awabdy/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myBrian">About  <i class="fas fa-chevron-down"></i></button>
</div>


<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/11/paul-manners-1.jpg" width="516" height="516">
<h3 class = "bio-name" >Paul Manners</h3>
<h4 class="bio-title">Finance Director</h4>
<div id="debDesc">
Paul is a Senior Finance and Operations Executive with deep experience ranging from early stage startups to Fortune 100 companies. Paul's past experience includes Finance roles at Novartis and Johnson & Johnson.
<br>
<a href="https://www.linkedin.com/in/paulmanners/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myDeb">About  <i class="fas fa-chevron-down"></i></button>
</div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/05/IMG_0601-scaled.jpg" width="516" height="516">
<h3 class = "bio-name" >Kyungjin Hong, PhD</h3>
<h5 class ="bio-title">Senior Bioengineer</h5>
<div id="kyungjinDesc">
Kyungjin is a Biomedical Engineer with a data-driven mindset. With interdisciplinary backgrounds ranging from surface modification chemistry, nano- and microfabrication to microfluidics and biosensing, she designs and develops medical devices from early concept, prototyping, testing to production. As an ardent learner, Kyungjin is always seeking new learning opportunities and enjoys wearing different “new” hats at Sandstone. Kyungjin earned her PhD in Biomedical Engineering from UC Davis.
<br>
<a href="https://www.linkedin.com/in/ellie-kyungjin-hong-0a408868/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myKyungjin">About  <i class="fas fa-chevron-down"></i></button>
</div>



</div>
'''

'''
<div class = "row bios-all">

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/05/Website-Pic-Gabriella-e1591817865664.jpg" width="516" height="516">
<h3 class = "bio-name" >Gabriella Iacovetti</h3>
<h4 class="bio-title">Associate Scientist</h4>
<div id="gabriellaDesc">
Gabriella’s primary role is leading Sandstone’s bioscience efforts. While everyone at Sandstone wears many hats, some of hers include clinical coordination, experimental design and execution, and leading on the job training for the R+D team. Prior to Sandstone, she studied biology at Azusa Pacific University and worked at Donor Network West where she partnered with hospital staff throughout California and Nevada to facilitate tissue donation for transplantation and research. She enjoys combining her passion for biology with her fast-paced clinical experience as a part of Sandstone’s innovative team!
<br>
<a href="https://www.linkedin.com/in/gabriella-iacovetti/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myGabriella">About  <i class="fas fa-chevron-down"></i></button>
</div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2021/05/bhumika_pic.jpg" width="516" height="516">
<h3 class = "bio-name" >Bhumika Harshita</h3>
<h4 class="bio-title">Sr. QA Associate</h4>
<div id="bhumikaDesc">
Bhumika Harshita earned a Bachelor’s degree in Psychology and is a certified ISO 13485 :2016 Auditor. Her excellent 15+ years of experience and background in Quality Management Systems from Medical Devices companies like Johnson and Johnson, Corning Life Science and few start ups. 
<br>
<a href="https://www.linkedin.com/in/bhumika-h-54448a4/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myBhumika">About  <i class="fas fa-chevron-down"></i></button>
 </div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/06/IMG_2587-crop-e1591816396747.jpg" width="516" height="516">
<h3 class = "bio-name" >Jon Epperson</h3>
<h5 class ="bio-title">Operations and Research Associate</h5>
<div id="jonDesc">
Jon joined Sandstone in 2013 after graduating from UC Berkeley with a B.A. in Cell and Molecular Biology. Jon has been heavily involved in the development, clinical trials, and manufacturing scale up of Sandstone's Trak Male Fertility Testing System, and supports Sandstone's operations, quality systems management, and manufacturing activities. <br> <a href="https://www.linkedin.com/in/jon-epperson-2a111474/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myJon">About  <i class="fas fa-chevron-down"></i></button>
</div>

</div>
'''
'''
<div class = "row bios-all">

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2021/05/maggie_pic.jpg" width="516" height="516" >
<h3 class = "bio-name" >Maggie Cruz</h3>
<h5 class ="bio-title">Office Manager</h5>
<div id="tifanyDesc">
Maggie Cruz began her career in finance as CFO in the print advertising industry. She earned a scholarship to attend Pepperdine’s Grazadio Business School. Leading to a career in business operations and administration. She is currently Sandstone’s Office Manager. She has extensive experience in the start-up space and has assisted 4 companies through growth, mergers, and acquisitions.<br><a href="https://www.linkedin.com/in/margaretcruz/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myTifany">About  <i class="fas fa-chevron-down"></i></button>
</div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/05/Photo.jpg" width="516" height="516">
<h3 class = "bio-name" >Jason Ragar</h3>
<h4 class="bio-title">Mechanical Engineer</h4>
<div id="jasonDesc">
Jason recently earned his B.S. in Mechanical Engineering from San Jose State University. At Sandstone, he assists with process development and secondary operations. Jason enjoys making things, whether it is something simple or complex, and he also likes to learn more about the world around him. <br><a href="https://www.linkedin.com/in/jasonpaulragar/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myJason">About  <i class="fas fa-chevron-down"></i></button>
</div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2021/05/shannon_pic.jpg" width="516" height="516" >
<h3 class = "bio-name" >Shannon Setzer</h3>
<h4 class="bio-title">Research Assistant</h4>
<div id="shannonDesc">
Shannon recently received her B.S. in Biological Sciences from the University of California, Santa Barbara.  She works in the lab on the biological side of the Research and Development projects here at Sandstone.  She loves learning new skills and is always excited to tackle whatever new challenge comes her way.<br><a href="https://www.linkedin.com/in/shannon-setzer-438703186/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myShannon">About  <i class="fas fa-chevron-down"></i></button>
 </div>

</div>
'''

## JavaScript
'''
<!--Allows JQuery to be used across page--!>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<!--Click on about button for description to slide down and up. Each person has their own function.--!>
<script type="text/javascript"> 

$(".myGary").click(function(){
    $("#garyDesc").slideToggle();
  });

$(".myKaren").click(function(){
    $("#karenDesc").slideToggle();
  });

$(".myGreg").click(function(){
    $("#gregDesc").slideToggle();
  });

$(".myUlrich").click(function(){
    $("#ulrichDesc").slideToggle();
  });

$(".about-btn").click(function(){
    $(this).children("i").toggleClass("fa-chevron-down fa-chevron-up");
  });

</script>

'''
'''
<script type="text/javascript"> 

$(".myBrian").click(function(){
    $("#brianDesc").slideToggle();
  });

$(".myDeb").click(function(){
    $("#debDesc").slideToggle();
  });

$(".myDave").click(function(){
    $("#daveDesc").slideToggle();
  });

</script>
'''
'''
<script type="text/javascript"> 

$(".myKyungjin").click(function(){
    $("#kyungjinDesc").slideToggle();
  });

$(".myGabriella").click(function(){
    $("#gabriellaDesc").slideToggle();
  });

$(".myMaggie").click(function(){
    $("#maggieDesc").slideToggle();
  });

</script>
'''
'''
<script type="text/javascript"> 

$(".myJon").click(function(){
    $("#jonDesc").slideToggle();
  });

$(".myBhumika").click(function(){
    $("#bhumikaDesc").slideToggle();
  });

$(".myShannon").click(function(){
    $("#shannonDesc").slideToggle();
  });

$(".myTifany").click(function(){
    $("#tifanyDesc").slideToggle();
  });

$(".myJason").click(function(){
    $("#jasonDesc").slideToggle();
  });

</script>
'''


## Board of Directors
'''
<div class = "row bios-all">

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/08/GGA-headshot-SQUARE-for-SDx-website-IMG_4212.jpeg" width="516" height="516" >
<h3 class = "bio-name" >Gary Altman, PhD</h3>
<h4 class="bio-title">Chief Executive Officer</h4>
<!--<div id="garyDesc">
Gary is an accomplished CEO, COO, VP and GM with more than 20-years’ experience in start-ups and global businesses including diagnostics, therapeutics, genomics, and life sciences. Gary's past positions include roles at Beckman Coulter, Human Longevity, and Sequoia Pharmaceuticals in addition to an expansive consulting career leading business and strategy initiatives for many small to mid-sized companies. Throughout his career, Gary has launched products, led turnarounds, expanded markets, raised Angel and Venture Capital, and managed budgets up to $250M.
<br>
<a href="https://www.linkedin.com/in/garygaltman/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>
<button type="button" class="about-btn myGary">About  <i class="fas fa-chevron-down"></i></button>--!>
</div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/05/Sommer_pic_lowres-e1591816256572.jpg" width="516" height="516" >
<h3 class = "bio-name" >Greg Sommer, PhD</h3>
<h4 class="bio-title">CoFounder and Executive Vice President</h4>
<!--<div id="gregDesc">
Greg has over 15 years experience developing point-of-care diagnostic tools. Prior to cofounding Sandstone, he was a Senior Research Scientist at Sandia National Laboratories where he led R&D in point-of-care diagnostic technologies for biodefense and emergency preparedness applications. Greg is a co-inventor on over 20 issued patents, a co-author on 15 peer-reviewed publications, was named a 2015 Bay Area "40 Under 40", and earned his Mechanical Engineering degrees from Iowa State University and the University of Michigan.
<br>
<a href="https://www.linkedin.com/in/gregsommer1/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div></a>--!>
<!--<button type="button" class="about-btn myGreg">About  <i class="fas fa-chevron-down"></i></button>--!>
</div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/03/BobEaston.jpg" width="516" height="516">
<h3 class = "bio-name" >Bob Easton</h3>
<h4 class="bio-title">Co-Chairman at Bionest Partners</h4>
<!--<div id="bobDesc">
Jason is a recent grad from San Jose State University where he earned his B.S. in Mechanical Engineering. At Sandstone, he assists with process development and secondary operations. Jason enjoys making things, whether it is something simple or complex, and he also likes to learn more about the world around him. <br><a href="https://www.linkedin.com/in/jasonpaulragar/" target="_blank"><i class="fa fa-linkedin"></i>
</div></a>--!>
<!--<button type="button" class="about-btn myBob">About  <i class="fas fa-chevron-down"></i></button>--!>
</div>




</div>
'''
'''
<div class = "row bios-all">

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/03/BetoPallares.jpg" width="516" height="516" >
<h3 class = "bio-name" >Beto Pallares, PhD</h3>
<h5 class ="bio-title">Managing Director, Hunt Family Holdings</h5>
<!--<div id="betoDesc">
A recent graduate from UC Davis, Tifany helps design and prototype new devices for Sandstone. She loves learning new things on the engineering and biology side of things, as she is very curious about everything, and loves helping any way she can. In her spare time, she likes to exercise, try lots of food, be with family and friends, and play with her cat. She also enjoys reading, writing and learning even more things! <br><a href="https://www.linkedin.com/in/tifanypan/" target="_blank"><i class="fa fa-linkedin"></i>
</div></a>--!>
<!--<button type="button" class="about-btn myBeto">About  <i class="fas fa-chevron-down"></i></button>--!>
</div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/03/FaithCharles.jpg" width="516" height="516">
<h3 class = "bio-name" >Faith Charles, JD</h3>
<h4 class="bio-title">Partner, Corporate Transactions & Securities Practice/Chair, Life Sciences Group at Thomson Hine LLP</h4>
<!--<div id="faithDesc">
Jason is a recent grad from San Jose State University where he earned his B.S. in Mechanical Engineering. At Sandstone, he assists with process development and secondary operations. Jason enjoys making things, whether it is something simple or complex, and he also likes to learn more about the world around him. <br><a href="https://www.linkedin.com/in/jasonpaulragar/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>--!>
<!--<button type="button" class="about-btn myJason">About  <i class="fas fa-chevron-down"></i></button>--!>
</div>

<div class ="col-lg-4 col-sm-6 bio-col">
</div>


</div>
'''
## Scientific Advisory Board
'''<div class = "row bios-all">

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2018/08/eisenberg-e1534251327140.jpg" width="516" height="516" >
<h3 class = "bio-name" >Michael Eisenberg, MD</h3>
<h5 class ="bio-title">Director of Reproductive Medicine, Stanford University Medical Center</h5>
<!--<div id="priyaDesc">
A recent graduate from UC Davis, Tifany helps design and prototype new devices for Sandstone. She loves learning new things on the engineering and biology side of things, as she is very curious about everything, and loves helping any way she can. In her spare time, she likes to exercise, try lots of food, be with family and friends, and play with her cat. She also enjoys reading, writing and learning even more things! <br><a href="https://www.linkedin.com/in/tifanypan/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>--!>
<!--<button type="button" class="about-btn myPriya">About  <i class="fas fa-chevron-down"></i></button>--!>
</div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2019/03/Steven_Lipkin.jpg" width="516" height="516">
<h3 class = "bio-name" >Steven Lipkin, MD PhD</h3>
<h4 class="bio-title">Professor of Medicine, Clinical Genetics, Weill Cornell Medicine</h4>
<!--<div id="stevenDesc">
Jason is a recent grad from San Jose State University where he earned his B.S. in Mechanical Engineering. At Sandstone, he assists with process development and secondary operations. Jason enjoys making things, whether it is something simple or complex, and he also likes to learn more about the world around him. <br><a href="https://www.linkedin.com/in/jasonpaulragar/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>--!>
<!--<button type="button" class="about-btn mySteven">About  <i class="fas fa-chevron-down"></i></button>--!>
</div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2019/03/pollard.jpeg" width="516" height="516" >
<h3 class = "bio-name" >Elizabeth Hutt Pollard</h3>
<h5 class ="bio-title">Director of Reproductive Medicine, Stanford University Medical Center</h5>
<!--<div id="priyaDesc">
A recent graduate from UC Davis, Tifany helps design and prototype new devices for Sandstone. She loves learning new things on the engineering and biology side of things, as she is very curious about everything, and loves helping any way she can. In her spare time, she likes to exercise, try lots of food, be with family and friends, and play with her cat. She also enjoys reading, writing and learning even more things! <br><a href="https://www.linkedin.com/in/tifanypan/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>--!>
<!--<button type="button" class="about-btn myPriya">About  <i class="fas fa-chevron-down"></i></button>--!>
</div>

</div>
'''

'''
<div class = "row bios-all">

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2020/03/PriyaBalachandran.jpg" width="516" height="516" >
<h3 class = "bio-name" >Priya Balachandran</h3>
<h5 class ="bio-title">Chief Operating Officer at Applied Silver, Inc.</h5>
<!--<div id="priyaDesc">
A recent graduate from UC Davis, Tifany helps design and prototype new devices for Sandstone. She loves learning new things on the engineering and biology side of things, as she is very curious about everything, and loves helping any way she can. In her spare time, she likes to exercise, try lots of food, be with family and friends, and play with her cat. She also enjoys reading, writing and learning even more things! <br><a href="https://www.linkedin.com/in/tifanypan/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>--!>
<!--<button type="button" class="about-btn myPriya">About  <i class="fas fa-chevron-down"></i></button>--!>
</div>

<div class ="col-lg-4 col-md-50 col-xl-25 bio-col">
<img class="bio-images" src="https://sandstonedx.com/wp-content/uploads/2018/08/alukal-e1534251370432.jpeg" width="516" height="516">
<h3 class = "bio-name" >Joseph Alukal, MD</h3>
<h4 class="bio-title">Clinical Associate Professor, NYU Langone Health Department of Urology</h4>
<!--<div id="josephDesc">
Jason is a recent grad from San Jose State University where he earned his B.S. in Mechanical Engineering. At Sandstone, he assists with process development and secondary operations. Jason enjoys making things, whether it is something simple or complex, and he also likes to learn more about the world around him. <br><a href="https://www.linkedin.com/in/jasonpaulragar/" target="_blank"><i class="fa fa-linkedin"></i></a>
</div>--!>
<!--<button type="button" class="about-btn myJoseph">About  <i class="fas fa-chevron-down"></i></button>--!>
</div>

<div class ="col-lg-4 col-sm-6 bio-col">
</div>

</div>
'''

