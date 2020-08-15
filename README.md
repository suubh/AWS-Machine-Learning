# AWS-Machine-Learning
Get your Gaussian Package.

## For installing the package using pip .Perform the following steps.
<h2>Clone into your directory.</h2>
<h3>For Windows the prerequisite are:</h3><br>
<ol>
      <li>Check whether virtualenv is installed or not using - <strong>virtualenv - version</strong></li>
      <li>If not then install using - <strong>pip install vitualenv</strong></li>
      <li>Then try to create a virtual environment by using the following commands.</li>
      <ul>
            <li><strong>virtualenv environmentname</strong></li>
            <li><strong>environmentname\Scripts\activate</strong></li>
      </ul>
      <li>The above commands will activate a virtual environment</li> .
</ol>
<h3>For Linux or Ubuntu:</h3><br>
<ol>
      <li>Check whether virtualenv is installed or not using <strong>virtualenv - version</strong></li>
      <li>If not then install using - <strong>pip install vitualenv</strong></li>
      <li>Then try to create a virtual environment by using the following commands.</li>
      <ul>
            <li><strong>python3 -m venv environmentname</strong></li>
            <li><strong>source environmentname/bin/activate</strong></li>
      </ul>
      <li>This will activate the virtual environment.</li>
</ol>
<hr> 
<h3>Now to Install our Package </h3>
<p>Open the cmd (for Windows) or terminal(for Linux). Move into the proper directory ,in my case to the directory which contains the distributions and setup.py files .Then create a virtual environment using the above steps. When the virtual environment is ready and open then use the pip to install your package pip install </p>

<h3>To check - </h3>
<ul>
      <li>from distributions import Gaussian</li>
      <li>gaussian_one=Gaussian(10,3)</li>
      <li>gaussian_one.mean</li>
      <li>gaussian_one.stdev</li>
 </ul>

