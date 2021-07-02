# react-native-countdown-reset

## Getting started

`$ npm install react-native-countdown-reset --save`

### Mostly automatic installation

`$ react-native link react-native-countdown-reset`

## Usage
```javascript
import React from "react";
import CountdownReset from 'react-native-countdown-reset';

const CountdownReset = props => {
    return(
        <CountdownReset
            until={5}
            onFinish={() => alert('finished')}
            onPress={() => alert('hello')}
            size={20}
        />
    );
};
```
