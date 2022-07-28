# Image Feature Extraction
<h3>Image-Feature-extraction-using-Reinforcement-Learning.</h3>

**Our algorithm converts an `image dataset` into `tabular dataset` by extracting features of an image. 
<br>This algorithm is tested on simple problems like `digit recognition`, `hand-sign recognition` etc and is able to extract features. 
<br>For complex problems like extracting features from a human face image, we have not tested it and it probably won't work due to complexity of the problem.**

<h2>Demo :-</h1>
Input:
<p>
    <img src="resources/2.png" width="500" height="200" />
</p>

Output: `-169.0` , `-148.0`, `-153.0`, `-171.0`


<p></p>
<img src="resources/demo.gif" />

## Procedure: 
 * Calculate transition matrix of an Image
 * Preprocess it to reduce computation
 * Assign pixels to grids
 * Assign reward to each state
 * Find center of figure
 * Calculate return and using it extract features
 * At the end we get 4 features corresponding to each image
