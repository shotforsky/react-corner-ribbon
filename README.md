# Get Started

## install

```shell
$ npm install react-corner-ribbon --save
```

## usage

```jsx
import React from "react";
import CornerRibbon from "react-corner-ribbon";

class MyComponent extends React.Component {
  render() {
    return (
      <div style={{ position: "relative" }}>
        <CornerRibbon
          position="top-right"
          fontColor="white"
          backgroundColor="green"
        >
          AUTHORIZED
        </CornerRibbon>

        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat. Duis aute irure dolor in
          reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
          pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
          culpa qui officia deserunt mollit anim id est laborum.
        </p>
      </div>
    );
  }
}
```

## live demo
[CodeSandbox Demo](https://codesandbox.io/s/react-corner-ribbon-demo-qboxn)

![react-corner-ribbon](https://user-images.githubusercontent.com/14038117/106426773-28aef900-64a1-11eb-806a-851342d9eb97.png)
