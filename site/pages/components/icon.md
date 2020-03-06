import { Icon, Divider } from '@caple-ui/react';

# Icon

## Examples

```jsx header=기본&nbsp;예제
<>
  <Icon type="alert-circle" />
  <Icon type="close-circle" />
  <Icon type="check-circle" />
  <Icon type="arrow-left" />
  <Icon type="arrow-right" />
  <Icon type="chenvron-up" />
  <Icon type="chenvron-right" />
  <Icon type="chenvron-down" />
  <Icon type="chenvron-left" />
  <Icon type="caret-down" />
  <Icon type="caret-up" />
  <Icon type="caret-sort" />
  <Icon type="close" />
  <Icon type="edit" />
  <Icon type="gear" />
  <Icon type="reload" />
  <Icon type="star" />
  <Icon type="android" />
  <Icon type="apple" />
</>
```

```jsx header=색상&nbsp;변경&nbsp;예제
<>
  <Icon type="alert-circle" size={60} color="#637381" />
  <Icon type="close-circle" size={60} color="#BF1D08" />
  <Icon type="check-circle" size={60} color="#5C6AC4" />
</>
```

```jsx header=Spin&nbsp;예제
<Icon type="gear" size={60} spin />
```

```jsx header=Feather&nbsp;예제
<>
  <Icon.Feather type="bell" />
  <Icon.Feather type="clipboard" />
  <Icon.Feather type="cloud-rain" />
  <Icon.Feather type="git-branch" />
  <Icon.Feather type="wifi" />
  <Icon.Feather type="smile" />
  <Icon.Feather type="map" />
</>
```

## Props
| Name | Description | Type | Default | Required |
|:---:|:---:|:---:|:---:|:---:|
| **type** |  | string | - | false |
| **component** |  | ReactNode | - | false |
| **size** |  | number | 16 | false |
| **rotate** |  | number | - | false |
| **spin** |  | boolean | false | false |
| **color** |  | string | #212B36 | false |
| **onClick** |  | (event: MouseEvent) => void | - | false |
| **className** | 컴포넌트에 적용되는 className | string | - | false |
| **style** | 컴포넌트에 적용되는 style | CSSProperties | - | false |

<style jsx global>{`
  .component-container {
    padding-left: 40px;
    padding-right: 40px;
    text-align: center;
  }

  .caple-icon:not(:last-child) {
    margin-right: 10px;
  }
`}</style>