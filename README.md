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
          position="top-right" // OPTIONAL, default as "top-right"
          fontColor="#f0f0f0" // OPTIONAL, default as "#f0f0f0"
          backgroundColor="#2c7" // OPTIONAL, default as "#2c7"
          containerStyle={{}} // OPTIONAL, style of the ribbon
          style={{}} // OPTIONAL, style of ribbon content
          className="" // OPTIONAL, css class of ribbon
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

## Live demo
[CodeSandbox Demo](https://codesandbox.io/s/react-corner-ribbon-demo-qboxn)

![react-corner-ribbon](https://user-images.githubusercontent.com/14038117/116892650-9dd9c800-ac62-11eb-8041-e200313e7269.png)


## Change log
### v0.0.4(2021-05)
* add support of props like `className`, `style`, `containerStyle`.

### v0.0.3(2021-02)
* Initial version