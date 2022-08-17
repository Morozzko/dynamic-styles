<div style='display: flex;align-items: center;justify-content: center'>
<img src='https://svgshare.com/i/jfX.svg' alt=''/>
</div> 

# Make up layout inline

## Installation

```
yarn add @npm.piece/dynamic-styles @emotion/react @emotion/styled
```

```
npm i @npm.piece/dynamic-styles @emotion/react @emotion/styled
```

## Import

```jsx
import { style, IStyleContainer } from '@npm.piece/dynamic-styles'
import styled from '@emotion/styled/macro'
```

## Creating custom element

```jsx
const div = styled.div<IStyleContainer>`
  ${style};
`
```
