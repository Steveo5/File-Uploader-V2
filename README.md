
This is a simple Vue project that provides a drag and drop upload box.<br /> 
There is some simple frontend validation included such as min/max file sizes and file types

# Project structure

In **src** sub-folder we have VueJS application including
1. entry.js
2. FileUploaderV2.vue

# Setup

1. `npm  i fileuploaderv2`
2. `In your entry point (where Vue is included, such as app.js/main.js) add the code below`
```
import FileUploaderV2 from 'fileuploaderv2'
Vue.use(FileUploaderV2)
```

#### Project requirements
1. axios

#### Props
There is a number of props to use, most importantly you must set the post-url (where the files will go to)

1. `post-url` (string) where the files are sent to (one at a time as FormData, file name is just 'file')
2. `min-file-size` (number) size in kilobytes e.g 1000 would be 1MB
3. `min-file-size-message` (string) message to show when the file is under the minimum size
4. `max-file-size` (number) size in kilobytes e.g. 1000 would be 1MB
5. `max-file-size-message` (string) message to show when the file is larger then the max-file-size
6. `allowed-file-types` (array) file types that are allowed to be uploaded e.g. `['image/jpeg', 'image/png', 'image/jpg']`
7. `unknown-file-message` (string) which message to show when the above validation fails
8. `title` (string)


Any problems can be reported to https://github.com/Steveo5/file-uploader-v2
