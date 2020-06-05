# Download Time Prediction with linear regression

Using linear regression to predict the time of download according to to the file size

### Installation

installation requires [TenserFlow.js](https://www.tensorflow.org/js/)  to run.

You can use either the npm cli tool or yarn to install TensorFlow.js.

```sh
$ yarn add @tensorflow/tfjs

or

$ npm install @tensorflow/tfjs

or you can add this script tag to your main html file 

<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@2.0.0/dist/tf.min.js"></script>
```



### In-Browser functions

Run the following commands in your browser console(add .print() to get the results):

| Function | Utility |
| ------ | ------ |
| model.fit(data.size, data.time ,{epochs : Nbiteration}) | Train the model with the data from the data object and Nbiterations as the number of iteration |
|  model.evaluate(testTensors.size, testTensors.time) | estimate the quality of the model with test data in the testTensors |
|  model.predict(tf.tensor2d([[sizeOfTheFileInMB]])) | predict the time of download by passing the variable sizeOfTheFileInMB as the size of the file |






#### TensorFlow.js Documentation

See https://www.tensorflow.org/js


### Todos

 - Add other predicting features like Memory buffers, conectivity etc..




