# Classifier camera example

Runs a Edge Impulse machine learning model example in your workspace to be classified with your device camera.


## Installation

### Pre-requisites

* Node Js
* Camera
* If there is no prebuilt binary available for @iota/client in your system you need Rust and Cargo, to build it yourself. Install them [here](https://doc.rust-lang.org/cargo/getting-started/installation.html).

### Steps

* Clone this repo and navigate into it.
* Run ```npm install``` to install dependencies
* Run  ```npm install edge-impulse-linux -g --unsafe-perm```.



* Connect a camera and run ```npm start```
  * If you get an error that shows you all available cameras, run ```node index.js modelfile.eim <camera name>```


PS: You can download your model file by running the following command: ```npm run download``` that calls ```edge-impulse-linux-runner --download modelfile.eim``` script.
