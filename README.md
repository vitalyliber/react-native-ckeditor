# react-native-ckeditor

#### React Native CKEditor component with no native code for React Native apps built using WebView

## Installation

```
yarn add react-native-ckeditor
```

or

```
npm install --save react-native-ckeditor
```

and then

```jsx harmony
import CKEditor from 'react-native-ckeditor';
```

## Usage

Creating a CKEditor.js editor:


```jsx harmony
<CKEditor
  content={values.description}
  onChange={value => {
    setFieldValue('description', value);
  }}
/>
```
