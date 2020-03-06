import { Card, Checkbox, Header, Button, Input } from '@caple-ui/react';

# Checkbox

Checkbox 컴포넌트는

## Examples

```jsx header=기본&nbsp;예제
<>
  <Checkbox />
  <Checkbox disabled />
  <Checkbox error />
</>
```

```jsx header=Label&nbsp;예제
<Checkbox label="이용약관에 동의합니다." />
```

## Props
| Name | Description | Type | Default | Required |
|:---:|:---:|:---:|:---:|:---:|
| **name** |  | string | - | false |
| **label** |  | string | - | false |
| **value** |  | string | - | false |
| **checked** |  | boolean | false | false |
| **error** |  | boolean | false | false |
| **disabled** |  | boolean | false | false |
| **onChange** |  | boolean | - | false |
| **className** | 컴포넌트에 적용되는 className | string | - | false |
| **sttyle** | 컴포넌트에 적용되는 style | CSSProperties | - | false |

<style jsx global>{`
  .component-container {
    text-align: center;
  }

  .caple-checkbox:not(:last-child) {
    margin-right: 30px;
  }
`}</style>