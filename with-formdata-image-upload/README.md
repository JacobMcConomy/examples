# Image Upload Example

Try it at https://expo.io/@community/image-upload-example

## How to use

### Running the app

- `cd` into the `app` directory and run `yarn` or `npm install`
- Open `app` with `exp` or XDE, try it out.

### Running the server

- By default, the app will use a server that is already deployed in order to upload the image to S3. If you want to deploy your own, follow the steps in the [backend directory](https://github.com/expo/examples/tree/master/with-formdata-image-upload/backend). 

## The idea behind the example

A common requirement for apps is to be able to upload an image to a server. This example shows how you can use `ImagePicker` to snap a photo or grab it from your camera roll, then use `FormData` with `fetch` to upload it to a server. The `/backend` demsontrates a simple Node app that uploads an image to S3. The `/app` directory contains the Expo app that sends the image to that backend.