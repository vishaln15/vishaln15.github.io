---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
  }
.column {
  float: left;
  width: 33%;
  padding: 0 10px;
}
.row {margin: 0 -5px;}
.row:after {
  content: "";
  display: table;
  clear: both;
}
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  /* background-color: #f1f1f1; */
}
.sent-analysis{
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
  background: linear-gradient(-45deg, #ff4500, #ffb3cc, #ff6699, #ff66ff);
  background-size: 400% 400%;
  animation: gradient 5s ease infinite;
}
.neonatal {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
  background: linear-gradient(-45deg, #ff4500, #ffb3cc, #ff6699, #ff66ff);
  background-size: 400% 400%;
  animation: gradient 5s ease infinite;
}
.atrial{
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  /* background-image: url('/images/atrial.png'); */
  /* position: relative; */
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
  background: linear-gradient(-45deg, #ffa366, #ff668c, #ff6666, #ffb366);
	background-size: 400% 400%;
	animation: gradient 10s ease infinite;
}
.pysigpro{
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  /* background-image: url('/images/pysigpro.png'); */
  /* position: relative; */
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center; 
  background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
	background-size: 400% 400%;
	animation: gradient 5s ease infinite;
}
.techworld{
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  /* background-image: url('/images/techworld.png'); */
  /* position: relative; */
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
  background: linear-gradient(-45deg, #66ffff, #66d9ff, #66b3ff, #e6f2ff);
	background-size: 400% 400%;
  animation: gradient 5s ease infinite; 
}
.bradycardia{
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  /* background-image: url('/images/bradycardia.svg'); */
  /* position: relative; */
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
  background: linear-gradient(-45deg, #ccffcc, #33ff33, #00cc00, #66ff33);
	background-size: 400% 400%;
  animation: gradient 10s ease infinite; 
}
.flightdelay{
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  padding: 16px;
  text-align: center;
  /* background-image: url('/images/flightdelay.png'); */
  /* position: relative; */
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center; 
  background: linear-gradient(-45deg, #f2f3f2, #cccdcb, #a6a8a4, #c0c1be);
	background-size: 400% 400%;
  animation: gradient 5s ease infinite; 
}
@keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}
</style>

<h2>You can also view my full list of projects <a href="https://github.com/vishaln15" target="_blank">here</a>.</h2>
<br><br>

<div class="row">
  <div class="column">
    <div class="sent-analysis">
      <h3><u>Sentiment Analysis Flask App</u></h3>
      Small scale sentiment classification flask web app, containerized using Docker, and deployed on Google Cloud Run.

    </div>
  </div>

  <div class="column">
    <div class="neonatal">
      <h3><u>Neonatal Seizure Detection</u></h3>
      This repository contains code for my <a href="https://vishaln15.github.io/publication/2021-NeonatalSeizureDetection-2" style="text-decoration: none">research</a> on detecting neonatal seizures on low-memory devices. <br>
      <a href="https://github.com/vishaln15/NeonatalSeizureDetection/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/vishaln15/NeonatalSeizureDetection"></a>
      <a href="https://github.com/vishaln15/NeonatalSeizureDetection/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/vishaln15/NeonatalSeizureDetection?style=plastic"></a>
      <a href="https://github.com/vishaln15/NeonatalSeizureDetection" style="text-decoration: none"><i class="fab fa-github fa-spin"></i></a>
    </div>
  </div>

  <div class="column">
    <div class="atrial">
      <h3><u>Atrial Fibrillation Detection</u></h3>
      You can find the code for my <a href="https://vishaln15.github.io/publication/2021-OptimizedArrhythmiaDetection-1" style="text-decoration: none">work</a> on arrhythmia detection for ultra-edge devices in this repository. <br><br>
      <a href="https://github.com/vishaln15/OptimizedArrhythmiaDetection/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/vishaln15/OptimizedArrhythmiaDetection"></a>
      <a href="https://github.com/vishaln15/OptimizedArrhythmiaDetection/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/vishaln15/OptimizedArrhythmiaDetection"></a>
      <a href="https://github.com/vishaln15/NeonatalSeizureDetection" style="text-decoration: none"><i class="fab fa-github fa-spin"></i></a>
    </div>
  </div>

  <br>

<div class="row">  
  <div class="column">
    <div class="pysigpro">
      <h3><u>PySigPro</u></h3>
      PySigPro is an open-source WIP Python package aimed to extract and process features from physiological signals.<br>
      <a href="https://github.com/vishaln15/pysigpro/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/vishaln15/pysigpro"></a>
      <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/vishaln15/pysigpro">
      <a href="https://github.com/vishaln15/pysigpro" style="text-decoration: none"><i class="fab fa-github fa-spin"></i></a>
    </div>
  </div>
</div>

  <div class="column">
    <div class="techworld">
      <h3><u>TechWorld</u></h3>
      An Amazon-like website built using MERN stack with proper admin, users profile distinction.
      <a href="https://github.com/vishaln15/techworld/blob/master/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/vishaln15/techworld"></a>
      <a href="https://github.com/vishaln15/techworld/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/vishaln15/techworld"></a>
      <a href="https://github.com/vishaln15/techworld" style="text-decoration: none"><i class="fab fa-github fa-spin"></i></a>
    </div>
  </div>

  <div class="column">
    <div class="bradycardia">
      <h3><u>Bradycardia Prediction</u></h3>
      Bradycardia prediction using novel deep learning methods including Encoders & Seq2Seq.
      <a href="https://github.com/vishaln15/Bradycardia-Prediciton/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/vishaln15/Bradycardia-Prediciton"></a>
      <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vishaln15/Bradycardia-Prediciton">
      <a href="https://github.com/vishaln15/Bradycardia-Prediciton" style="text-decoration: none"><i class="fab fa-github fa-spin"></i></a>
    </div>
  </div>
</div>

<div class="row">
  <div class="column">
    <div class="flightdelay">
      <h3><u>Flight Delay Prediction</u></h3>
      A two-staged pipeline architecture to classify and predict the delay of flights in minutes.
      <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vishaln15/Flight-Delay-Prediction">
      <a href="https://github.com/vishaln15/Flight-Delay-Prediction/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/vishaln15/Flight-Delay-Prediction"></a>
      <a href="https://github.com/vishaln15/Flight-Delay-Prediction" style="text-decoration: none"><i class="fab fa-github fa-spin"></i></a>
    </div>
  </div>
</div>