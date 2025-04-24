# cs6476-computer-vision-problem-set-5-object-tracking-and-pedestrian-detection-solution



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs6476-computer-vision-problem-set-5-object-tracking-and-pedestrian-detection-solution/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;89701&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6476: Computer Vision Problem Set 5: Object Tracking and Pedestrian  Detection Solution&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<h1>Description</h1>
In this problem set you are going to implement tracking methods for image sequences and videos. The main algorithms you will be using are the Kalman and Particle Filters.

<h1>Learning Objectives</h1>
<ul>
<li>Identify which image processing methods work best in order to locate an object in a scene.</li>
<li>Learn to how object tracking in images works.</li>
<li>Explore different methods to build a tracking algorithm that relies on measurements and a prior state.</li>
<li>Create methods that can track an object when occlusions are present in the scene.</li>
</ul>
<h1>Problem Overview</h1>
<strong>Methods to be used: </strong>​You will design and implement a Kalman and a Particle filters from the ground up.

<strong>&nbsp;</strong>

<strong>RULES</strong>​: You may use image processing functions to find color channels, load images, find edges (such as with Canny), resize images.&nbsp; Don’t forget that those have a variety of parameters and you may need to experiment with them. There are certain functions that may not be allowed and are specified in the assignment’s autograder Piazza post.

Refer to this problem set’s autograder post for a list of banned function calls.

<strong><u>Please</u> do not use absolute paths in your submission code. All paths should be relative to the submission directory. Any submissions with absolute paths are in danger of receiving a penalty! </strong>

<strong>Obtaining the Starter Files: </strong>

Obtain the starter code from canvas under files.

<strong>Programming Instructions</strong>

Your main programming task is to complete the api described in the file ​<strong>ps5.py</strong>​.&nbsp; The driver program <strong>experiment.py</strong>​ helps to illustrate the intended use and will output the files needed for the writeup.

<h1>Write-up instructions</h1>
Create ​<strong>ps5_report.pdf</strong>​ – a PDF file that shows all your output for the problem set, including images labeled appropriately (by filename, e.g. ps5-1-a-1.png) so it is clear which section they are for and the small number of written responses necessary to answer some of the questions (as indicated).&nbsp; For a guide as to how to showcase your results, please refer to the powerpoint template for PS5.

&nbsp;

<strong>How to submit: </strong>

<ol>
<li>To submit your code, in the terminal window run the following command:</li>
</ol>
python submit.py ps05

<ol start="2">
<li>To submit the report, input images for part 5, and experiment.py, in the terminal window run the following command:</li>
</ol>
python submit.py ps05_report

<ol start="3">
<li>Submit your report pdf to gradescope.</li>
</ol>
&nbsp;

<strong>YOU MUST PERFORM ALL THREE STEPS. I.e. two commands in the terminal window and one upload to gradescope.&nbsp;&nbsp; </strong><strong>Only your last submission before the deadline will be counted for each of the code and</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong> the report. </strong>

&nbsp;

The following lines will appear:

GT Login required.

Username : &lt;GT username (same as T-square)&gt;

Password: &lt;GT password&gt;

Save the jwt?[y,N] &lt;either y or N if you want to save your credentials&gt;

&nbsp;

You should see the autograder’s feedback in the terminal window. Additionally, you can look at a history of all your submissions at <a href="https://bonnie.udacity.com/">https://bonnie.udacity.com</a>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <a href="https://bonnie.udacity.com/">/</a>

<h1>Grading</h1>
The assignment will be graded out of 100 points.&nbsp; The <strong>last submission</strong>​&nbsp;&nbsp;&nbsp;&nbsp; before the time limit will only be​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; considered. The code portion (autograder) represents <strong>50</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>%</strong> of the grade and the report the remaining​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>50%</strong>.​

&nbsp;

The images included in your report must be generated using experiment.py. This file should be set to be run as is to verify your results. <strong>Your report grade will be affected if we cannot reproduce your output</strong>​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong> images. </strong>

&nbsp;

The report grade breakdown is shown in the question heading. As for the code grade, you will be able to see it in the console message you receive when submitting.

&nbsp;

&nbsp;

<strong>Assignment Overview </strong>

<h1>1. The Kalman Filter [20 points]</h1>
The Kalman Filter (KF) is a method used to track linear dynamical systems with gaussian noise. Recall &nbsp;that both the predicted and the corrected states are gaussians, allowing us to keep the mean and covariance of the state in order to run this filter. Use the kalman filter on the provided images to track a moving circle.

&nbsp;

First we need to define the KF’s components. We will use the notation presented in the lectures for the N-dimensional case.

&nbsp;

<u>State vector:</u>

We represent the filter’s state using the current position and velocities in the x, y plane. We will not use acceleration in our exercise. <em>X </em>= [<em>x</em>, <em>y</em>, <em>v<sub>x</sub></em> ,<em>v<sub>y</sub></em>]

&nbsp;

<u>Dynamics Model transition 4×4 matrix </u><em>D<sub>t </sub></em><u>:</u>

This matrix will map the equations below to the state components. Determine how this 4×4 matrix can be used to represent these equations using the state vector. <em>x</em><em>t </em>= <em>x</em><em>t</em>−1 + <em>v</em><em>x</em>Δ<em>t y</em><em>t </em>= <em>y</em><em>t</em>−1 + <em>v</em><em>y</em>Δ<em>t</em>

Δ<em>t</em> = 1 for simplicity

&nbsp;

<u>State and Covariance prediction:</u>

We assume that the state vector prediction is based on a linear transformation using the transition matrix <em><sup>D</sup></em><em><sub>t </sub></em>. And the covariance is obtained from the squaring operation plus the process noise <sup>Σ</sup><em><sub>d</sub></em><em>t </em>. We will also assume this noise is independent from each component in the state vector.

&nbsp;

<em>X</em>−<em>t </em>= <em>D</em><em>t</em> <em>X</em><em>t</em>+−1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Σ−<em>t </em>= <em>D</em><em>t</em> Σ<em>t</em>+−1 <em>D</em><em>Tt</em> + Σ<em>d</em><em>t</em>

&nbsp;

&nbsp;

Before we continue to the Correction state. We will define our sensor’s function as a way to obtain the object’s position. In our case we will use a template matching code to obtain these components. In order to make this a little more interesting, we will add some noise to these measurements.

&nbsp;

&nbsp;

&nbsp;

<u>Sensor measurement 2×4 matrix </u><em>M<sub>t </sub></em><u>:</u>

This matrix maps the available measurements to the state vector defined above. Because we can only obtain two values, <em>x</em> and <em>y </em>, it contains two rows and four columns.

&nbsp;

<u>Kalman Gain </u><em>K<sub>t </sub></em><u>:</u>

Using the measurement matrix, and the predicted covariance we can now compute the Kalman Gain. Here you will also define a measurement noise represented by Σ<em><sub>m</sub></em><em><sub>t </sub></em>.

<em>K</em><em>t</em> = Σ−<em>t </em><em>M</em><em>Tt </em>(<em>M</em><em>t</em>Σ−<em>t </em><em>M</em><em>Tt </em>+ Σ<em>m</em><em>t</em>)−1

&nbsp;

&nbsp;

<u>State and Covariance correction:</u>

Now that we have all the components we need, you will proceed to update the state and the covariance arrays. Notice that in order to update the state you will use the residual represented by the difference between the measurements obtained from the sensor (template matching function) <em>Y <sub>t</sub></em> and the predicted positions <em><sup>M</sup></em><em><sub>t</sub></em><em>X</em><sup>−</sup><em><sub>t </sub></em>.

<em>X</em><sup>+</sup><em><sub>t </sub></em>= <em>X</em><sup>−</sup><em><sub>t </sub></em>+ <em><sup>K</sup></em><em><sub>t</sub></em>(<em><sup>Y </sup></em><em><sub>t </sub></em>− <em><sup>M</sup></em><em><sub>t</sub></em><em>X</em><sup>−</sup><em><sub>t </sub></em>) <em><sup>Y </sup></em><em><sub>t</sub></em> are the measurements at time <em>t</em> Σ<sup>+</sup><em><sub>t </sub></em>= (<em>I </em>− <em><sup>K</sup></em><em><sub>t</sub></em><em><sup>M</sup></em><em><sub>t</sub></em>) Σ<sup>−</sup><em><sub>t </sub>I</em> is the identity matrix

&nbsp;

In the next iteration the updated state and covariance will be used in the prediction stage.

&nbsp;

This may seem like a lot but you will find coding this KF is not complicated. Complete the

KalmanFilter class with the process described above. We will split the tasks the following way:​

&nbsp;

<ol>
<li>Initialize the class defining the class arrays you will be using. Place these components in the</li>
</ol>
__init__(self, init_x, init_y) function. Here’s a reminder of what should be included in this part:

<ol>
<li>State vector ( <em>X </em>) with the initial <em>x</em> and <em>y</em></li>
<li>Covariance 4×4 array ( Σ ) initialized with a diagonal matrix with some value.</li>
</ol>
<ul>
<li>4×4 state transition matrix <em>D<sub>t</sub></em> 2×4 measurement matrix <em>M<sub>t</sub></em></li>
</ul>
<ol>
<li>4×4 process noise matrix <sup>Σ</sup><em><sub>d</sub></em><em>t</em></li>
<li>2×2 measurement noise matrix Σ<em><sub>m</sub></em><sub> <em>t</em></sub></li>
</ol>
<strong>&nbsp;</strong>

<strong>Code:&nbsp; </strong>__init__(self, init_x, init_y)​

<strong>&nbsp;</strong>

Complete the prediction state in predict(self). Here you will replace the class variables for the state and covariance arrays with the prediction process.

&nbsp;

<strong>Code: </strong>predict(self)​

&nbsp;

Finally, we need to correct the state and the covariances using the Kalman gain and the measurements obtained from our sensor.

&nbsp;

<strong>Code: </strong>​correct(self)

&nbsp;

<ol>
<li>The position estimation is performed by the function process(self, measurement_x, measurement_y) which uses the functions defined above. Now that you have finished creating the Kalman Filter, estimate the position of a bouncing circle. Use the images in the directory called ‘circle’ to find the circle’s position at each frame. Include the frame numbers described below in your report.</li>
</ol>
&nbsp;

<strong>Report: </strong>​Frames to record: 10, 30, 59, 99 – Input: ​<strong>circle/0000.jpg to circle/0099.jpg.</strong>

<ul>
<li>Output: ​<strong>ps5-1-b-1.png, ps5-1-b-2.png, ps5-1-b-3.png, ps5-1-b-4.png</strong></li>
</ul>
&nbsp;

<ol>
<li>Now let’s try with a more complicated scene using the same filter. We will find and track pedestrians in a video. This means we need to update our sensor with a function that can locate people in an image. Fortunately, there is a function in OpenCV that can help us with this task using Histogram of Gradients (HoG) descriptors. This object contains a method called detectMultiScale that returns the bounding boxes for each person in the scene along with the detection weight associated to it.</li>
</ol>
&nbsp;

Use the sequence of images in the ‘walking’ directory to detect and follow the man crossing the street using the output from the HoG detector as the measurements and the Kalman Filter.

&nbsp;

<strong>Report: </strong>​Frames to record: 10, 33, 84, 159 – Input: ​<strong>walking/001.jpg to walking/159.jpg.</strong>

<ul>
<li>Output: ​<strong>ps5-1-c-1.png, ps5-1-c-2.png, ps5-1-c-3.png, ps5-1-c-4.png</strong></li>
</ul>
<h2>2. The Particle Filter [25 points]</h2>
Recall that we need a variety of elements:

<ul>
<li>a ​<em>model</em>​ – this is the “thing” that is actually being tracked. Maybe it’s a patch, a contour, or some other description of an entity;</li>
<li>a representation of ​<em>state</em>​ <em>x<sub>t</sub></em> that describes the state of the model at time <em>t </em>;</li>
<li>a ​<em>dynamics</em>​ ​<em>model</em>​ <em>p</em>(<em>x<sub>t</sub></em> | <em>x<sub>t</sub></em><sub>−1</sub>) that describes the distribution of the state at time <em>t</em> given the state at <em>t </em>− 1 ;</li>
<li>a ​<em>measurement</em>​ <em>z<sub>t </sub></em>that somehow captures the data of the current image; and finally,</li>
<li>a ​<em>sensor model </em><em>p</em>(<em>z<sub>t</sub></em> | <em>x<sub>t</sub></em>) that gives the likelihood of a measurement given the state. For Bayesian-based tracking, we assume that at time <em>t </em>− 1 we have a belief about the state represented as a ​<em>density</em>​ <em>p</em>(<em>x<sub>t</sub></em><sub>−1</sub>) , and that given some measurements​ <em>z<sub>t</sub> </em>​at time​ <em>t </em>​we update our ​<em>Belief</em>​ by computing the posterior density:</li>
</ul>
<em>Bel(x</em>​<em>t</em><sub>​</sub><em>) </em><sub>​</sub><sup>∝</sup>​<em> p(z</em>​<em>t</em><sub>​</sub><em>|x</em>​<em>t</em><sub>​</sub><em>)p(x</em>​<em>t</em><sub>​</sub><em>|u</em>​<em>t</em><sub>​</sub><em>,x</em>​<em>t-1</em><sub>​</sub><em>)Bel(x</em>​<em>t-1</em><sub>​</sub><em>)</em>

&nbsp;

In class we discussed both the theory and the implementation specifics behind particle filtering. The algorithm sketch is provided in the slides and it describes a single update of the particle filter. What is left up to the coder are several details including what is the model, what is the state, the number of particles, the dynamics/control function <em>p</em>(<em>x<sub>t</sub></em> | <em>x<sub>t</sub></em><sub>−1</sub>, <em>u<sub>t</sub></em>) , the measurement function <em>p</em>(<em>z<sub>t</sub></em> | <em>x<sub>t</sub></em>) , and the initial distribution of particles.

&nbsp;

For this question, you will to need track an image patch template taken from the first frame of the video. For this assignment the model is simply going to be the image patch, and the state will be only the 2D center location of the patch. Thus each particle will be a (u, v) pixel location (where u and v are the row and column number respectively) representing a proposed location for the center of the template window.

&nbsp;

We will be using a basic function to estimate the dissimilarity between the image patch and a window of equal size in the current image, the Mean Squared Error:

&nbsp;

The funny indexing is just because (u, v) are indexed from 1 to M (or N) but the state &lt;u<sub>p</sub>​ ,<sub>​</sub> v<sub>p</sub>​ <sub>​</sub>&gt; is the location of the center. Notice the above equation can be simplified by using array operations. Remember you are calculating the <u>Mean</u>​ of the <u>Squared​ Error</u> between two images, a template and a patch of the image.

&nbsp;

These images are color and you will convert them to grayscale can do the tracking in either the full color image, or in grayscale, or even in the green channel. If you use color, there would be an outer summation over the three color channels. If you want to use grayscale, you can use cvtColor in OpenCV or just use a weighted sum of R,G,B to get a luma value (try weights of 0.3, 0.58, and 0.12).

&nbsp;

MSE, of course, only indicates how dissimilar the image patch is, whereas we need a similarity measure so that more similar patches are more likely. Thus, we will use a squared exponential equation (Gaussian) to convert this into a usable measurement function:

&nbsp;

To start out, you might use a value of σ<sub>MSE</sub>​ = 10 (for grayscale in 0-255 range) but you might need to change this value.

For the dynamics we’re going to use normally distributed noise since the object movements can be unpredictable and often current velocity isn’t indicative of future motion; so our dynamics model is merely

which is just a fancy way to say you add a little bit of Gaussian noise to both<em> u </em>​ ​and<em> v </em>​ ​independently.

&nbsp;

The number of particles and initial distribution are up to you to figure out. You may need to tune your parameters for these to get better tracking/performance.

&nbsp;

In order to visualize the tracker’s behavior you will need to overlay each successive frame with the following elements:

<ul>
<li>Every particle’s <em>(</em>​ <em>x,y)</em> location in the distribution should be plotted by drawing a colored dot point on the image. Remember that this should be the center of the window, not the corner.</li>
<li>Draw the rectangle of the tracking window associated with the Bayesian estimate for the current location which is simply the <em>weighted</em>​ ​ mean of the <em>(</em>​ <em>x,y)</em>​ of the particles.</li>
<li>Finally we need to get some sense of the standard deviation or spread of the distribution. First, find the distance of every particle to the weighted mean. Next, take the weighted sum of these distances and plot a circle centered at the weighted mean with this radius.</li>
</ul>
&nbsp;

You will have to produce these visuals for select frames but you will not have to submit the entire video. For reading the frames OpenCV users should look at the class VideoCapture​ .​ For sampling based on a distribution, see the functions numpy.random.multinomial or numpy.random.choice​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .​

&nbsp;

<ol>
<li>Implement the particle filter. You can find the bounding box for the initial position in template_rect – this is your template. Tweak the parameters including window size until you can get the tracker to follow this object. Run the tracker and save the video frames described below with the visualizations overlaid.</li>
</ol>
&nbsp;

<strong>Classes, methods</strong>:​ Define a class <strong>ParticleFilter</strong>​ , with the following methods:​

<ul>
<li>__init__(frame, template, **kwargs): (constructor) Initialize particle filter object.</li>
<li>get_error_metric(template, frame_cutout): Calculates the error metric used (i.e. MSE).</li>
<li>resample_particles(): Returns a list of particles resampled based on their weights.</li>
<li>process(frame): Process a frame (image) of video and update filter state.</li>
</ul>
* Hint: You should call resample_particles() and get_error_metrics() here.

<ul>
<li>render(frame_out): Visualize current particle filter state.</li>
</ul>
&nbsp;

A helper function, run_particle_filter()​ ​, has been provided to run your particle filter on a video and collect the output. You can also display every video frame to verify that your particle filter is working properly.

&nbsp;

<em>Note: The helper function </em>​<em>run_particle_filter() can save the template image patch and outputs generated by your </em>​<em>render()</em>​<em> method for desired frames. See template code for details. </em>

&nbsp;

<strong>Report: </strong>Frames to record: 10, 30, 59, 99​

<ul>
<li>Input: <strong>circle/0000.jpg to circle/0099.jpg.</strong>​</li>
<li>Output: <strong>ps5-2-a-1.png, ps5-2-a-2.png, ps5-2-a-3.png, ps5-2-a-4.png</strong>​</li>
</ul>
<strong>&nbsp;</strong>

<ol>
<li>Now use the particle filter with a noisy video:</li>
</ol>
<strong>Report: </strong>Frames to record: 10, 33, 84, 99​

<ul>
<li>Input: <strong>pres_debate_noisy/000.jpg to pres_debate_noisy/099.jpg.</strong>​</li>
<li>Output: <strong>ps5-2-b-1.png, ps5-2-b-2.png, ps5-2-b-3.png, ps5-2-b-4.png</strong>​</li>
</ul>
<h2>3. Changes in Appearance [10 points]</h2>
In the last section you were working with a static template assuming that the target will not change in shape. This can be addressed by updating the model’s appearance over time.

&nbsp;

Modify your existing tracker to include a step which uses the history to update the tracking window model. We can accomplish this using what’s called an Infinite Impulse Response (IIR) filter. The concept is simple: we first find the best tracking window for the current particle distribution as displayed in the visualizations. Then we just update the current window model to be a weighted sum of the last model and the current best estimate.

&nbsp;

where <em>Best(t)</em>​ is the patch of the <strong>best</strong>​<strong> estimate or mean estimate</strong>​. It’s easy to see that by recursively updating this sum, the window implements an exponentially decaying weighted sum of (all) the past windows. For this assignment, you may assume t​ to be the frame number, in lieu of a time measure.​

&nbsp;

<ol>
<li>Implement the appearance model update feature. Run the tracker on the presidential debate images and adjust parameters until you can track the person’s hand (the one not holding the microphone). Your tracker’s bounding box should only contain the hand at all times. Run the tracker and save the video frames described below with the visualizations overlaid.</li>
</ol>
&nbsp;

<strong>Classes, methods</strong>:​ Derive a class AppearanceModelPF from ParticleFilter, retaining the <u>same interface</u> – i.e., with methods process() and render(), as defined above. The constructor and process() method should transparently handle model updates. You can supply additional keyword arguments to the constructor, if needed.

&nbsp;

<strong>Report: </strong>Frames to record: 22, 50, 160​

<ul>
<li>Input: <strong>pres_debate/000.jpg to pres_debate/165.jpg.</strong>​</li>
<li>Output: <strong>ps5-3-a-1.png, ps5-3-a-2.png, ps5-3-a-3.png</strong>​</li>
</ul>
<h2>4. Particle Filters and Occlusions [20 points]</h2>
For this part we will work with a much more difficult video to perform tracking with, <strong>pedestrians.mp4</strong>​ .​ We’d like to be able to track the blond-haired woman (the one with the white jacket) as she crosses the road. If you try applying your adaptive tracker to this video, you will probably find that you will have difficulty dealing simultaneously with occlusion and the perspective shift as the woman walks away from the camera. Thus, we need some way of relying less on updating our appearance model from previous frames and more on a more sophisticated model of the dynamics of the figure we want to track.

&nbsp;

Expand your appearance model to include window size as another parameter. This will change the representation of your particles. You are highly recommended to use cv2.resize for your implementation to resize the template to track.

&nbsp;

<ol>
<li>Run the tracker and save the video frames described below with the visualizations overlaid. You will receive full credit if you can reliably track (illustrate this with the rectangle outline) all the way to the end of the street and deal gracefully with the occlusions (reasonable tracking at frame 300). The tracking box must track the person’s position and size.</li>
</ol>
&nbsp;

<strong>Classes, methods</strong>:​ Derive a class MDParticleFilter from AppearanceModelPF, retaining the <u>same interface</u> – i.e., with methods process() and render(), as defined above. The constructor and process() method should transparently handle model updates in appearance and dynamics. You can supply additional keyword arguments to the constructor and other methods, if needed.

&nbsp;

<strong>Report: </strong>Frames to record 40, 100, 240, 300.​

<ul>
<li>Input: <strong>pedestrians/000.jpg to pedestrians/319.jpg.</strong>​</li>
<li>Output: <strong>ps5-4-a-1.png, ps5-4-a-2.png, ps5-4-a-3.png, and ps5-4-a-4.png</strong>​</li>
<li>Text Answer: <strong>Describe</strong>​<strong> what you did. How did you modify the Particle Filter class to continue tracking after occlusions?</strong></li>
</ul>
<h2>5. Tracking Multiple Targets [20 points]</h2>
Now use either a kalman or particle filter to track multiple targets as they move through the given video. Use the sequence of images in the TUD-Campus directory to detect the people shown below.

&nbsp;

&nbsp;

&nbsp;

<strong>Report</strong>:​ Frames to record: 29, 56, 71

<ul>
<li>Input: <strong>TUD-Campus/01.jpg to TUD-Campus/71.jpg</strong>​ .​</li>
<li>Output: <strong>ps5-5-a-1.png, ps5-5-a-2.png, ps5-5-a-3.png</strong>​</li>
<li>Text Answer: Describe what you did. How different it was to use a KF vs PF? Which one worked best and why? Include details about any modifications you had to apply to handle multiple targets.</li>
</ul>
<h2>6. Challenge Problem: Detect Pedestrians from a moving camera [5 points]</h2>
Finally, detect pedestrians from the given video of a moving camera. Use the images in the directory ‘follow’ to track the man with the hat holding a white plastic bag.

&nbsp;

<strong>Report</strong>​: Frames to record: 60, 160, 186 – Input: ​<strong>follow/001.jpg to follow/186.jpg</strong>​.

<ul>
<li>Output: ​<strong>ps5-6-a-1.png, ps5-6-a-2.png, ps5-6-a-3.png</strong></li>
<li>Text Answer: Describe what you did. Did this task present any additional challenges compared to the previous sections? Include details about any modifications you had to apply.</li>
</ul>
&nbsp;

&nbsp;

&nbsp;
