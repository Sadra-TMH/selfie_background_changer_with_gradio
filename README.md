# Selfie background changer 

This app is written using ``opencv, mediapipe`` and ``gradio`` to make a webapp.<br>
To use it first you need to install needed packages:<br>
<pre>
pip install opencv-python mediapipe gradio
</pre>
Then you should open background_eraser.ipynb and run all cells.<br>
At the last cell you will get a local url like [http://127.0.0.1:7863/](http://127.0.0.1:7863/). <br>By clicking on it you will be transferred to the gradio webapp.<br>

# Use the webapp
To use the app you need to first upload two pictures. One should be a selfie that contains a person (image section), the other one should be a background image that you want your selfie's background to be replaced by.<br>
Then hit submit button and get the results!<br>

# Example
<img src="/example/selfie_example.jpg" alt="web app example" />
