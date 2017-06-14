# STA141C-BIG-DATA-HIGH-Performance-STA-Comp
<HTML>
<HEAD>
   <META HTTP-EQUIV="Content-Type" CONTENT="text/html; charset=iso-8859-1">
   <META NAME="Author" CONTENT="Bobo">
   <META NAME="GENERATOR" CONTENT="Mozilla/4.04 [en] (Win95; I) [Netscape]">
   <TITLE>Scalable Machine Learning</TITLE>
</HEAD>
<BODY>
    <big><big><span style="font-family: Arial; font-weight: bold;">
				STA 141C 
				Big Data & High Performance Statistical Computing (Spring 2017)</span><br style="font-family: Arial; font-weight: bold;">
        <span style="font-family: Arial; font-weight: bold;">Spring 2017</span></big></big><br style="font-family: Arial;">
    <br style="font-family: Arial;">
    <span style="font-family: Arial;">Tues/Thurs 12:10 pm - 13:30 pm</span><br style="font-family: Arial;">
    
    <style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-536870145 1073786111 1 0 415 0;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-parent:"";
	margin:0in;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;}
.MsoChpDefault
	{mso-style-type:export-only;
	mso-default-props:yes;
	font-size:10.0pt;
	mso-ansi-font-size:10.0pt;
	mso-bidi-font-size:10.0pt;}
@page WordSection1
	{size:8.5in 11.0in;
	margin:1.0in 1.0in 1.0in 1.0in;
	mso-header-margin:.5in;
	mso-footer-margin:.5in;
	mso-paper-source:0;}
div.WordSection1
	{page:WordSection1;}
-->
</style><!--[if gte mso 10]>
<style>
 /* Style Definitions */
 table.MsoNormalTable
	{mso-style-name:"Table Normal";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-parent:"";
	mso-padding-alt:0in 5.4pt 0in 5.4pt;
	mso-para-margin:0in;
	mso-para-margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:10.0pt;
	font-family:"Times New Roman","serif";}
</style>
<![endif]--><br style="font-family: Arial;">
    <br style="font-family: Arial;">
    <hr style="width: 100%; height: 2px; font-family: Arial;"><br style="font-family: Arial;">
    <table style="text-align: left; width: 100%; font-family: Arial;" border="0" cellpadding="2" cellspacing="2">
      <tbody>
        <tr>
          <td style="vertical-align: top;"><span style="font-weight:
              bold;">Instructor</span>: <a href="http://www.cs.utexas.edu/~cjhsieh/"><span style="font-weight: bold;">Cho-Jui Hsieh</span></a><br>
		  Office location: Mathematical Sciences Building (MSB) 4232 <br>
		  Email: chohsieh@ucdavis.edu <br>
	      Office hours: Wednesday 2pm-3pm<br>
	  </td>
  </tr>
  <tr>
          <td style="vertical-align: top;"><span style="font-weight:
				  bold;">TA</span>: Huan Zhang (ecezhang@ucdavis.edu), Clark Fitzgerald (clarkfitzg@gmail.com) <br>
			  TA office hours: Tuesday 2pm-4pm (MSB 1117) <br>
		</td>
		</tr>
	<tr>
<!--          <td style="vertical-align: top;"><span style="font-weight:
              bold;">TA</span>: <a href="http://www.cs.utexas.edu/~cjhsieh/"><span style="font-weight: bold;">Carlos Colman Meixner</span></a><br>
		  Email:  cecolmanmeixner@ucdavis.edu<br> 
	  </td> -->
		  </tr>
        <tr>
          <td style="vertical-align: top;"><br>
          </td>
        </tr>
        <tr>
			<!--          <td style="vertical-align: top;"><span style="font-weight:
              bold;">TA</span>: <a href="mailto:shalini@cs.utexas.edu"></a><br>
            Office location: ???<br>
			Office hours: ???<br> -->
          </td>
        </tr>
      </tbody>
    </table>
    <br style="font-family: Arial;">
    <hr style="width: 100%; height: 2px; font-family: Arial;"><br style="font-family: Arial;">
	<big><span style="font-family: Arial; font-weight: bold;">Announcements</span></big><br>
	<!--	Here's the <a href="https://docs.google.com/document/d/1CHhMQGKT2p9DWDRIwyGspZHZDurJQk9pqVOIlTn52GM/edit?usp=sharing"> tentitive paper presentation schedule</a>. Please email TA and me (by October 13, 11:59 PM) your group members and the selected topic. -->
	<a href="final_project_proposal.pdf">final project proposal guidline </a>
	<br>
	<a href="note_linear_algebra.pdf">Basic Linear Algebra (Notes) </a>
	<br>
	<br>  
    <big><span style="font-family: Arial; font-weight: bold;">Overview</span></big><br style="font-family: Arial;">
    <br style="font-family: Arial;">
    <div style="margin-left: 40px;"><span style="font-family: Arial;"><span style="font-weight: bold;">Course description</span> <br>
			<br>
			This course explores aspects of scaling statistical computing for large data and simulations. 
			It will cover (1) How to write a good program for analyzing data, (2) Data-intensive computing for statistical models, 
			and (3) How to parallelize the code for handling big data. The goal is to learn practical techniques
			to efficiently handle real world data mining tasks
			and competitions.  
			 <br>
      </span><br>
     <br>
      <span style="font-family: Arial;"> <span style="font-weight:
          bold;">Syllabus</span><br>
        <br>
      </span><span style="font-family: Arial;"></span>&nbsp;&nbsp;&nbsp; <span style="font-family: Arial;">A high-level summary of the syllabus
        is as follows:<br>
      </span>
      <blockquote><span style="font-family: Arial;">I. Statistical Programming (in Python)</span><br>
        <span style="font-family: Arial;"></span>
        <ul>
          <li><font face="Arial">Basic python programming</font></li>
          <li><font face="Arial">Numpy and Scipy</font></li>
          <li><font face="Arial">Big-O: analyzing the speed of your program</font></li>
		  <li><font face="Arial">Basic algorithms and data structure</font></li>
        </ul>
        <font face="Arial">II. Advanced statistical computing</font><br>
        <ul>
          <li><font face="Arial">Linear algebra and applications</font></li>
          <li><font face="Arial">Optimization and applications</font></li>
		  <li><font face="Arial">Clustering, classfication, regression, EM<br>
          <li><font face="Arial">Scikit-learn<br>
            </font></li>
        </ul>
        <font face="Arial">III. Parallel computing </font><br>
        <ul>
			<li><font face="Arial">Multicore programming</font></li>
			<li><font face="Arial">Distributed (MapReduce)</font></li>
        </ul>
      </blockquote>
	  <font face="Arial"> </font></div>
  <br>
  
     <big><span style="font-family: Arial; font-weight: bold;">Grading Policy</span></big><br style="font-family: Arial;">
	<br style="font-family: Arial;">
    <div style="margin-left: 40px;"><span style="font-family: Arial;">Grades will be determined as follows: 
        </span><br style="font-family: Arial;">
    </div>
    <div style="margin-left: 40px;">
      <ul>
		  <li><span style="font-family: Arial;">Homework (60%)</span></li>
        <li><span style="font-family: Arial;">Final project (30%)</span></li>
        <li><span style="font-family: Arial;">Class participation,
            including attendance (10%)</span></li>
      </ul>
      <br style="font-family: Arial;">
  </div>
    <br style="font-family: Arial;">
    <hr style="width: 100%; height: 2px; font-family: Arial;"><br style="font-family: Arial;">

    <big><span style="font-family: Arial; font-weight: bold;">Schedule</span></big><br>
	<br>
    <div style="margin-left: 10px;">
      <ul>
		    <li><span style="font-family: Arial; font-weight: bold">Course Intro</span></li>
			<div style="margin-left: 20px;">
				<div style="line-height:50%;">
					    <br>
					</div>
					<li>	  Slides:  <a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture0.pdf"> lecture_0</a> </li>
	</div><br>
		<li><span style="font-family: Arial; font-weight: bold">Basic Python Programming</span></li>
		<div style="margin-left: 20px;">
	<div style="line-height:50%;">
					    <br>
					</div>
					<li>	  Slides:  [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture1.pdf"> lecture_1 </a>]
					[<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture2.pdf"> lecture_2 </a>]
					</li>
					<li>Reading Material: 
					<ul>
						<li ><a href="http://www.scipy-lectures.org/"> Scientific Computing in Python </a> </li> 
						<li> <a href="https://jsharpna.github.io/141B/"> STA 141B (Prof. Sharpnack) </a> </li> 
						</ul>
						</li> 
						<li>Homework: [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/hw1.pdf"> homework_1 </a>], [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/hw1_data.zip"> hw1_data </a>]</li> 
	</div><br>

		<li><span style="font-family: Arial; font-weight: bold">Time complexity analysis, basic algorithms and data structures</span></li>
		<div style="margin-left: 20px;">
				<div style="line-height:50%;">
					    <br>
					</div>


		<li>	  Slides: [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture3.pdf"> lecture_3 </a>]
[<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture4.pdf"> lecture_4 </a>]
 </li>
 <li>Reading Material: <a href="https://www.tutorialspoint.com/data_structures_algorithms/"> tutorial_point</a></li> 
		<li>Homework: </li><br> 
	</div>

		<li><span style="font-family: Arial; font-weight: bold">Numerical Linear Algebra for Statistics</span></li>
		<div style="margin-left: 20px;">
				<div style="line-height:50%;">
					    <br>
					</div>
		<li>	  Slides:  [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture5.pdf"> lecture_5 </a>] 
 [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture6.pdf"> lecture_6 </a>] 
 [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture7.pdf"> lecture_7 </a>] 
 [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/note_linear_algebra.pdf"> lecture_note_linear_algebra </a>] 
</li>
		<li>Reading Material:
		[<a href="http://www.math.cornell.edu/~mec/Winter2009/RalucaRemus/Lecture3/lecture3.html"> PageRank </a>] 
		[<a href="http://www.math.cornell.edu/~mec/Winter2009/RalucaRemus/Lecture4/lecture4.html">
			Hubs & Authorities</a>]
		[<a href="http://www.aclweb.org/anthology/Q15-1016"> word2vec</a>]

		
		</li> 
		<li>Homework: [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/hw2.pdf"> homework_2 </a>] </li> 
	</div><br>

		<li><span style="font-family: Arial; font-weight: bold">Numerical Optimization for Statistics</span></li>
		<div style="margin-left: 20px;">
				<div style="line-height:50%;">
					    <br>
					</div>

		<li>	  Slides: 
		 [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/note_optimization_1.pdf"> lecture_notes_optimization_1 </a>] 
				 [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/note_optimization_2.pdf"> lecture_notes_optimization_2</a>]  
 [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture8.pdf"> lecture_8 </a>] 
				 [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/note_optimization_3.pdf"> lecture_notes_optimization_3</a>]  

		</li>
		<li>Reading Material: 		</li> 
		<li>Homework: [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/hw3.pdf"> homework_3 </a>] </li> 

	</div><br>

		<li><span style="font-family: Arial; font-weight: bold">Computing for Statistical Models</span></li>
		<div style="margin-left: 20px;">
		<div style="line-height:50%;">
					    <br>
					</div>
		<li>	  Slides: 
 [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture9.pdf"> lecture_9 </a>] 
 [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture10.pdf"> lecture_10 </a>] 

		</li>
		<li>Reading Material: </li> 
		<li>Homework: </li> 
	</div> <br>

		<li><span style="font-family: Arial; font-weight: bold">Multicore and Distributed Computing</span></li>
		<div style="margin-left: 20px;">
		<div style="line-height:50%;">
					    <br>
					</div>
		<li>	  Slides: 
 [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/lecture11.pdf"> lecture_11 </a>] 
		</li>
		<li>Reading Material: 
		[<a href="http://sebastianraschka.com/Articles/2014_multiprocessing.html"> introduction to python multiprocessing </a>]
		[<a href="https://pymotw.com/2/multiprocessing/basics.html">tutorial with more detail </a>]
		</li> 
		<li>Homework: [<a href="http://www.stat.ucdavis.edu/~chohsieh/teaching/STA141C_Spring2017/hw4.pdf"> homework_4 </a>] </li> 
	</div> <br>


      </ul>
      <br style="font-family: Arial;">
  </div>
 


    <br>
    <br>
    <br>
    <span style="font-family: &#39;Arial&#39;,&#39;sans-serif&#39;;"></span><br>

</BODY>
</HTML>
