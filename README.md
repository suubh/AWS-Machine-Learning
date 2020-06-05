# AWS-Machine-Learning
Get your Gaussian Package.

## For installing the package using pip .Perform the following steps.
>Clone into your directory.
>For Windows the prerequisite are:
1.Check whether virtualenv is installed or not using >virtualenv - version.
2.If not then install using <pip install vitualenv>
3.Then try to create a virtual environment by using the following commands.
      >virtualenv environmentname
      >environmentname\Scripts\activate
4.The above commands will activate a virtual environment .

>For Linux or Ubuntu:
1.Check whether virtualenv is installed or not using >virtualenv - version.
2.If not then install using <pip install vitualenv>
3.Then try to create a virtual environment by using the following commands.
    >python3 -m venv environmentname
    >source environmentname/bin/activate
4.This will activate the virtual environment.
  
>Now to Install our Package , open the cmd (for Windows) or terminal(for Linux). Move into the proper directory ,in my case to the directory which contains the distributions and setup.py files .Then create a virtual environment using the above steps. When the virtual environment is ready and open then use the pip to install your package<pip install .>

>To check
>from distributions import Gaussian
>gaussian_one=Gaussian(10,3)
>gaussian_one.mean
>gaussian_one.stdev
