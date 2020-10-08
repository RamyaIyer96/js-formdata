# to-formdata

A library to convert Object/Array to form-data streams.
# Support
This library is supported by any JavaScript platforms

## Install
### Install using npm
`npm install --save to-formdata`

### Install using yarn
`yarn add to-formdata`

# Usage

### How to use
`const toFormData=require('to-formdata')`
### Examples

```
const toFormData= require('to-formdata')

const file = new File(["foo"],"foo.txt",{
    type:"text/plain"
});

const data = {
    name: "foo",
    gender: "Male",
    image: file
};

const converted = toFormData(data);
```
## ES6

```
import toFormData from 'to-formdata


const file = new File(["foo"],"foo.txt",{
    type:"text/plain"
});

const data = {
    name: "foo",
    gender: "Male",
    image: file
};

const converted = toFormData(data);
```