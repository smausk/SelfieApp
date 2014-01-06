# Selfie: Face Detection Sample App

Sample app demonstrating use of Android's front facing camera, face detection library, and drawing on an image that you can then save and share.

## Camera

The MainActivity opens a front-facing camera, the proper camera to use for selfies.

## Face Detection

Once the image is captured, faces are detected in the image in the EditActivity. On each of these faces, the location of the eyes is used to properly size and place a hat, glasses, and tie on each person.

## Drawing & Sharing

The EditActivity also demonstrates the use of drawing on a canvas through "stickers". When the user selects a sticker, the sticker's Bitmap is drawn on the image exactly at the point where the user touches the image. Finally, you can share your custom creation by pressing the share button, which saves the image as a file and then uses a standard Android share intent.