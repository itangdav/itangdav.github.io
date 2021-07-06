---
layout: page
title: Selected Projects
permalink: /projects
exclude: false
---

<link rel="stylesheet" href="styles.css"/>
<link rel="stylesheet" href="bootstrapiso.css"/>

<div class="bootstrapiso">
  <div class="card text-white bg-dark mb-3" style="width: 900px; margin-top: 10px; margin-bottom: 10px;">
    <div class="card-body" style="text-align:center;">
      <img style="height:250px;" alt="ERG Image" src="/images/(21,10,4)Graph1.png"/>
      <h5 class="card-title" style="margin-top: 10px;">Database of ERGs</h5>
      <p class="card-text">This is a complete enumeration of non-triangle-free edge regular graphs generated for my summer research project at Carnegie Mellon University in 2021. </p>
      <a href="/DatabaseOfERGs/" class="btn btn-primary">Check it out here.</a>
    </div>
  </div>
  <div class="card text-white bg-dark mb-3" style="width: 900px;">
    <div class="card-body" style="text-align:center;">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/2rzQRaaD_DQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <h5 class="card-title" style="margin-top: 10px;">Havalion Castle Rescue</h5>
      <p class="card-text">This is a game we created for Hack the North 2020++ using the Ubisoft Hacker's NEST API. The demo video is above. </p>
      <a href="/Havalion-Castle-Rescue" class="btn btn-primary">Read more about it here.</a>
    </div>
  </div>
  <div class="card text-white bg-dark mb-3" style="width: 900px;">
    <div class="card-body">
      <h5 class="card-title" style="margin-top: 10px; text-align: center;">Sudoku Solvers</h5>
      <ol>
        <li style="margin-bottom:10px"><p style="font-weight:bold">Algorithmic Sudoku Solver in Java</p>
          
        This is a modular sudoku solver where you can easily add more algorithms and it attempts to solve the puzzle by using as many algorithmic steps as possible. Once it gets stuck, it will make an optimized guess before continuing with using algorithms and use backtracking if it encounters an unsolvable board. It also keeps track of the number of guesses which is a good approxiamation of the difficulty of a puzzle.
        <div style="text-align:center"><img style="height:240px;margin-left:5px; margin-right:5px;" alt="Sudoku Image" src="/images/sudokuboard1.png"/> <img style="height:240px;margin-left:5px; margin-right:5px;" alt="Code Image" src="/images/JavaSudoku1.jpg"/></div>
        <a href="/Sudoku-Solver" class="btn btn-primary" style="margin-top: 10px;">Read more about it here.</a>
          
          
        </li>
      <li style="margin-bottom:10px"><p style="font-weight:bold">Convolutional Neural Network Sudoku Solver in Python</p>
        
        Using the Tensorflow package in Python, I trained a convolutional neural network to solve Sudoku puzzles on more than a million distinct training cases. It only has a mid-80s percent testing accuracy after several weeks of training, which can be improved further with more training data. Yet, using a step-by-step interpretation of the data, I am able to get the solution for any input to be very close or exactly the solution.
        <div style="text-align:center"><img style="height:240px;margin-left:5px; margin-right:5px;" alt="Code Image" src="/images/TensorflowSudoku1.jpg"/> <img style="height:240px;margin-left:5px; margin-right:5px;" alt="Training Image" src="/images/TensorflowSudoku2.jpg"/></div>
        <a href="/TensorflowSudoku" class="btn btn-primary" style="margin-top: 10px;">Read more about it here.</a>
        
        
        </li>
      </ol>
    </div>
  </div>
</div>




