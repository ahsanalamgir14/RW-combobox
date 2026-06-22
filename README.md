# React Combo-box

> A flexible and easy accessible combo-box for the React JS.

[![NPM](https://img.shields.io/npm/v/rw-combobox-react.svg)](https://www.npmjs.com/package/rw-combobox-react) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com) [![Netlify Status](https://api.netlify.com/api/v1/badges/246cf76a-5156-4e4f-bb83-c98de91b581f/deploy-status)](https://app.netlify.com/sites/react-combobox/deploys)

## Install

```bash
npm install --save rw-combobox-react
```

## Usage

```tsx
import React from 'react'
import ComboBox from 'rw-combobox-react'
import 'rw-combobox-react/dist/index.css'

const ComboBoxExample = () => {
  const data = [
    'America',
    'India',
    'Australia',
    'Argentina',
    'Ireland',
    'Indonesia',
    'Iceland',
    'Japan'
  ]
  return <ComboBox options={data} enableAutocomplete />
}
```

## Guide And Documentation

Read the full Documentation <a style="color:#cc3a38" href="https://react-combobox.netlify.app/">here</a>.

## Demo

To view the demo of the Combo Box component in the code sandbox. Click <a style="color:#cc3a38" href="https://codesandbox.io/s/distracted-saha-k8kti?file=/src/App.js">here</a>.

## License

MIT © [ahsanalamgir14](https://github.com/ahsanalamgir14)
