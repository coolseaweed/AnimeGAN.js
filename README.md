
# AnimeGAN.js
This project allows online photo animation. [Click here to have a try.](https://animegan.js.org) I suggest you use a device with WebGL support. See the support of Tensorflow.js [here](https://js.tensorflow.org/debug/).

Behind the scene, this project runs [AnimeGAN](https://github.com/TachibanaYoshino/AnimeGAN) online with [TensorFlow.js](https://www.tensorflow.org/js). The model that AnimeGAN.js uses comes from AnimeGAN's released model. You could use the one in `public` if you want to run it locally. If you want to create another model, you need to export it from TensorFlow and then use tools [TensorFlow.js](https://www.tensorflow.org/js) provides to convert.

## An example of AnimeGAN
![AnimeGAN](https://raw.githubusercontent.com/TachibanaYoshino/AnimeGAN/master/result/Hayao/photo_result/1%20(37).jpg)

## For developers

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
