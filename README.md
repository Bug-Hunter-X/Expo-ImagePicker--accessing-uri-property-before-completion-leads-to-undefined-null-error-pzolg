# Expo ImagePicker Asynchronous URI Access Bug

This repository demonstrates a common bug encountered when using the Expo ImagePicker library. The problem lies in accessing the `uri` property of a selected image before the asynchronous image selection process is finished.  This often results in `uri` being `undefined` or `null`, leading to errors during image processing.

The `bug.js` file shows the problematic code. The `bugSolution.js` file provides a corrected version using Promises or async/await to handle the asynchronous nature of the ImagePicker.