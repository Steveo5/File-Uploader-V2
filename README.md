
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

