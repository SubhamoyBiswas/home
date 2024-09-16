<style type='text/css'>
  * {
    list-style: none;
    text-decoration: none;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Open Sans', sans-serif;
  }
  /*body {
    background: #f5f6fa;
  }
  .wrapper .sidebar{
    background: rgb(5, 68, 104);
    position: fixed;
    top: 0;
    left: 0;
    width: 150px;
    height: 100%;
    padding: 20px 0;
    transition: all 0.5s ease;
  }
  .wrapper .sidebar ul li{
    display: inline;
  }
  .wrapper .sidebar ul li a{
    display: block;
    padding: 13px 30px;
    border-bottom: 1px solid #000;
    color: rgb(241, 237, 237);
    font-size: 15px;
    font-family: 'Lucida Grande'
    position: relative;
  }
  .wrapper .sidebar ul li a .icon{
    color: #dee4ec;
    width: 30px;
    display: inline-block;
  }
  .wrapper .sidebar ul li a:hover,
  .wrapper .sidebar ul li a.active{
    color: #0c7db1;
    background:white;
    border-right: 2px solid rgb(5, 68, 104);
  }
  .wrapper .sidebar ul li a:hover .icon,
  .wrapper .sidebar ul li a.active .icon{
    color: #0c7db1;
  }
  .wrapper .sidebar ul li a:hover:before,
  .wrapper .sidebar ul li a.active:before{
    display: block;
  }
  .wrapper .content{
    display: inline-block;
    margin-left: 0px;
  } */
</style>

<div class="wrapper">
        <!--<div class="sidebar">
           <ul>
                <li>
                    <a href="https://subhamoybiswas.github.io/home/" class="active">
                        <span class="item">About</span>
                    </a>
                </li>
                <li>
                    <a href="https://subhamoybiswas.github.io/home/projects.html">
                        <span class="item">Projects</span>
                    </a>
                </li>
                <li>
                    <a href="https://subhamoybiswas.github.io/home/publications.html">
                        <span class="item">Publications</span>
                    </a>
                </li>
                <li>
                    <a href="https://subhamoybiswas.github.io/home/awards.html">
                        <span class="item">Awards</span>
                    </a>
                </li>
                <li>
                    <a href="https://subhamoybiswas.github.io/home/CV.html">
                        <span class="item">CV</span>
                    </a>
                </li>
            </ul>
        </div> 
        <div class="content">
            Hi, I am Subhamoy!<br>
            I am a research candidate in the Master of Applied Science in Electrical and Computer Engineering program at University of Waterloo, advised by <a href="https://uwaterloo.ca/electrical-computer-engineering/profile/m2poudin">Prof. Mahla Poudineh</a> at the <a href="https://uwaterloo.ca/integrated-devices-early-awareness-lab/">Integrated Devices for Early Disease Awareness and Translational Applications (IDEATION) Lab</a>. I am currently working on:<br>
            <br>1. time-series models for long-term glucose monitoring and forecasting diabetic ketoacidosis in patients
            <br>2. fabrication and optimization of minimally-invasive microneedles for bioanalyte detection
            <br><img src="Background.png" alt="alt text" width="500" align="middle"/>
            <br>
            <br>
            <br>I received my Bachelor of Engineering degree with Honours in Electrical Engineering from Jadavpur University, India. During my undergraduate years, I developed multiple computational frameworks for applications like detecting therapeutic drug targets in viruses and simulating the dynamics of atrial fibrillation. My research interest lies in the domains of computational biology and biomedical devices and in applying machine learning approaches to solve state-of-the-art bioengineering problems.
            <br>
            <br>
            <br>I have enjoyed working at the following institutions:
            <br>
            <br>
            <img src="UW_logo.png" alt="alt text" height="80" align="middle"/>    <img src="UdeM_logo.png" alt="alt text" height="80" align="middle"/>    <img src="JU_logo.png" alt="alt text" height="80" align="middle"/>
            <br>
            <br>
            <br>In my free time, I enjoy reading and watching horror stories.
            <br>
            <br>
        </div> -->
</div>
## Projects
<br>
<ul>
	<li><font size="+1"><b>Machine learning-assisted continuous glucose and ketone monitoring for diabetic ketoacidosis</b> - University of Waterloo</font><ul>
		<li> Supervisor - <a href="https://uwaterloo.ca/electrical-computer-engineering/profile/m2poudin">Prof. Mahla Poudineh</a></li>
		<li> September 1, 2022 - August 13, 2024</li>
		<li> <a href="https://hdl.handle.net/10012/20794">Thesis link</a></li><br>
		<li> Summary - Type 1 diabetes has affected millions of people worldwide, and rigorous tracking of blood glucose levels is critical for providing care and avoiding severe complications like hyperglycemia and diabetic ketoacidosis. Continuous glucose monitoring (CGM) devices have emerged as an effective tool to detect glucose levels from interstitial fluid (ISF) instead of blood and offer real-time treatment. ISF usually serves as a rich source of biomarkers, enabling minimally-invasive detection for continuous health monitoring through ISF-based sensors like CGM. Various machine learning works in the past have used these CGM measurements to forecast glucose levels and predict events like hypoglycemia or any potential risks. However, despite their effective performances, most have focused on short-term predictions, neglecting the importance of long-term forecasting for better insulin therapy. In the first half of this thesis, we present an encoder-decoder architecture for long-term forecasting of future BG levels that expands the forecasting horizon from conventional 1 hour up to 3 hours. This work has the potential to improve the precision of state-of-the-art insulin delivery platforms for effective diabetes management. In addition to this, despite the advantages offered by ISF-based sensors in general, they encounter a significant challenge related to the sensing delay in the transferring of target analytes like glucose from blood to ISF. Particularly, this delay can vary significantly from subject to subject, and if not estimated properly, can impact the accuracy of the sensor measurements. Prior machine learning frameworks for continuous measurement of glucose from ISF have not adequately accounted for this existing delay between blood and ISF. Therefore, in the second half of this thesis, we investigate and quantify sensing delays in the transfer of glucose and ketone bodies from blood to ISF using decision-tree-based algorithms by considering a case study of diabetic rats that emulate the conditions of diabetic ketoacidosis. Accounting for this delay in the measurement process can eventually improve the accuracy of such sensors and offer a more personalized response during continuous monitoring of glucose and ketone bodies for better insulin dosing.</li><br>
	</ul></li>
	<!-- <li><font size="+1"><b>International Master's Award of Excellence</b> - University of Waterloo</font><ul>
		<li> $12,500 - Awarded based on academic excellence demonstrated through application for admission to graduate program</li><br>
	</ul></li>
	<li><font size="+1"><b>Globalink Graduate Fellowship</b> - Mitacs Inc., CA</font><ul>
		<li> $15,000 - Awarded for pursuing research masters in Canada</li><br>
	</ul></li>
	<li><font size="+1"><b>Senior Scholarship</b> - Jagadis Bose National Science Talent Search, India</font><ul>
		<li> $3,500 (converted) - Awarded to “top 73/2000+” undergraduate applicants in West Bengal, India, based on a 3-level competition in natural sciences</li><br>
	</ul></li> -->
</ul>
<br>
<!-- ### [<< return to homepage](README.md) -->
