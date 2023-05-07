Download Link: https://assignmentchef.com/product/solved-mae-3210-homework-5
<br>
<ol>

 <li></li>

</ol>

<ul>

 <li>Develop an algorithm which, for a given function <em>f</em>(<em>x</em>), interval bounds <em>a </em>and <em>b </em>with <em>a &lt; b</em>, and a prescribed number of subintervals <em>n</em>, applies the multiple application trapezoidal rule to approximate the integral.</li>

</ul>

<ol start="2">

 <li>Develop an algorithm which, for a given function <em>f</em>(<em>x</em>), interval bounds <em>a </em>and <em>b </em>with <em>a &lt; b</em>, and a prescribed number of subintervals <em>n</em>, approximates the integral</li>

</ol>

according to the following procedure:

<ul>

 <li>If <em>n </em>= 1, it applies the trapezoidal rule.</li>

 <li>If <em>n </em>is even, it applies the multiple application Simpson’s 1/3 rule.</li>

 <li>If <em>n </em>≥ 3 and <em>n </em>is odd, it applies the multiple application Simpson’s 1/3 rule on the first <em>n </em>− 3 subintervals, and applies the Simpson’s 3/8 rule on the last three subintervals.</li>

</ul>

<ol start="3">

 <li>Develop an algorithm which, for a given function <em>f</em>(<em>x</em>), interval bounds <em>a </em>and <em>b</em></li>

</ol>

with <em>a &lt; b</em>, and error tolerance per subinterval <em>tol</em>, applies adaptive quadrature to approximate the integral (based on the pseudocode that was presented in the recorded lectures and can be found on page 642 of the textbook).

<ol start="4">

 <li>Apply the algorithms you developed in questions 1-3 above to approximate</li>

</ol>

for varying values of <em>n </em>and <em>tol</em>. Note that this integral is not easy to evaluate analytically! Using the true value of 0<em>.</em>602298, plot <em><sub>t </sub></em>as a function of <em>n </em>for the algorithms you developed in questions 1 and 2, and plot <em><sub>t </sub></em>as a function of <em>tol </em>for the algorithm you developed for question 3. Use your best judgement to determine appropriate ranges of values for <em>n </em>and <em>tol </em>to be included in the plots.