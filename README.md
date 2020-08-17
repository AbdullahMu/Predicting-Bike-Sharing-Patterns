---


---

<h1 id="predicting-bike-sharing-data-your-first-neural-network">Predicting Bike-Sharing Data (Your First Neural Network)</h1>
<h3 id="introduction">Introduction</h3>
<p>In this project, you’ll get to build a neural network from scratch to carry out a prediction problem on a real dataset! By building a neural network from the ground up, you’ll have a much better understanding of gradient descent, backpropagation, and other concepts that are important to know before we move to higher-level tools such as PyTorch. You’ll also get to see how to apply these networks to solve real prediction problems!</p>
<p>The data comes from the  <a href="https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset">UCI Machine Learning Database</a>.</p>
<h3 id="instructions">Instructions</h3>
<ol>
<li>
<p>Download the project materials from  <a href="https://github.com/udacity/deep-learning-v2-pytorch">our GitHub repository</a>. You can get download the repository with  <code>git clone https://github.com/udacity/deep-learning-v2-pytorch.git</code>. Our files in the GitHub repo are the most up to date, so it’s the best place to get the project files.</p>
</li>
<li>
<p>cd into the  <code>project-bikesharing</code>  directory.</p>
</li>
<li>
<p>Download anaconda or miniconda based on the instructions in the  <a href="https://classroom.udacity.com/nanodegrees/nd101/parts/2a9dba0b-28eb-4b0e-acfa-bdcf35680d90/modules/aba54606-cf35-4a77-b643-efec6a90bfa1/lessons/9e9ed61d-20c3-4431-95aa-a1099f28d601/concepts/4cdc5a26-1e54-4a69-8eb4-f15e37aaab7b">Anaconda lesson</a>. These are also outlined in the repository  <a href="https://github.com/udacity/deep-learning-v2-pytorch/blob/master/README.md">README</a>.</p>
</li>
<li>
<p>Create a new conda environment:</p>
<pre><code>conda create --name deep-learning python=3

</code></pre>
</li>
<li>
<p>Enter your new environment:</p>
<ul>
<li>Mac/Linux:  <code>&gt;&gt; source activate deep-learning</code></li>
<li>Windows:  <code>&gt;&gt; activate deep-learning</code></li>
</ul>
</li>
<li>
<p>Ensure you have  <code>numpy</code>,  <code>matplotlib</code>,  <code>pandas</code>, and  <code>jupyter notebook</code>  installed by doing the following:</p>
<pre><code>conda install numpy matplotlib pandas jupyter notebook

</code></pre>
</li>
<li>
<p>Run the following to open up the notebook server:</p>
<pre><code>jupyter notebook

</code></pre>
</li>
<li>
<p>In your browser, open  <code>Predicting_bike_sharing_data.ipynb</code>. Note that in the previous workspace this was called  <code>Your_first_neural_network.ipynb</code>  but the contents are the same, this is just a descriptive difference.</p>
</li>
<li>
<p>Follow the instructions in the notebook; they will lead you through the project. You’ll ultimately be editing the  <code>my_answers.py</code>  python file, whose components are imported into the notebook at various places.</p>
</li>
<li>
<p>Ensure you’ve passed the unit tests in the notebook and have taken a look at  <a href="https://review.udacity.com/#!/rubrics/2148/view">the rubric</a>  before you submit the project!</p>
</li>
</ol>
<p>If you need help running the notebook file, check out the  <a href="https://classroom.udacity.com/nanodegrees/nd101/parts/2a9dba0b-28eb-4b0e-acfa-bdcf35680d90/modules/aba54606-cf35-4a77-b643-efec6a90bfa1/lessons/13f4b7d6-92a9-468d-9008-084fc8b53a23/concepts/75e1eee0-5f81-4d5b-a1ca-eaebe3c91759">Jupyter notebook lesson</a>.</p>
<h3 id="submission">Submission</h3>
<p>Before submitting your solution to a reviewer, you are required to submit your project to Udacity’s Project Assistant, which will provide some initial feedback. It will give you feedback within a minute or two on whether your project will meet all specifications. It is possible to submit projects which do not pass all tests; you can expect to get feedback from your Udacity reviewer on these within 3-4 days.</p>
<p>The setup for the project assistant is simple. If you have not installed the client tool from a different Nanodegree program already, then you may do so with the command  <code>pip install udacity-pa</code>.</p>
<p>To submit your code to the project assistant, run  <code>udacity submit</code>  from within the top-level directory of the project. You will be prompted for a username and password. If you log in using Google or Facebook, visit  <a href="https://project-assistant.udacity.com/login">this link</a>  for alternate login instructions.</p>
<p>This process will create a zip file in your top-level directory named  <code>first_neural_network-result-.zip</code>, where there will be a number between  <code>result-</code>  and  <code>.zip</code>. This is the file that you should submit to the Udacity reviews system.</p>
<p>Upload that file into the system and hit Submit Project above!</p>
<p>If you run into any issues using the project assistant, please check  <a href="https://knowledge.udacity.com/questions/6299">this page</a>  to troubleshoot; feel free to post your problem in  <a href="https://knowledge.udacity.com/">Knowledge</a>  if it isn’t covered by one of the displayed cases!</p>
<h3 id="what-to-do-afterward">What to do afterward</h3>
<p>If you’re waiting for new content or to get the review back, here’s a great video from Frank Chen about the history of deep learning. It’s a 45 minute video, sort of a short documentary, starting in the 1950s and bringing us to the current boom in deep learning and artificial intelligence.</p>
<p><a href="https://youtu.be/ht6fLrar91U"><img src="https://s3.amazonaws.com/content.udacity-data.com/nd101/Screen+Shot+2017-01-27+at+11.38.54+AM.png" alt="AI and Deep Learning"></a></p>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

