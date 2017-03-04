# Pagination

Pagination component for Vue Bulma.

## Installation

```sh
$ npm install vue-bulma-pagination --save
# or
$ yarn add vue-bulma-pagination --save
```

## Examples

```vue
<template>
  <div>
    <pagination urlPrefix='/' currentPage=2 pageLength=100 /> 
  </div>
</template>

<script>
import Pagination from 'vue-bulma-pagination'

export default {
  components: {
    Pagination
  }
}
</script>
```
## doc

|  props    |  required   |   default   |  optional    |  desc | 
| ---- | ---- | ---- | ---- | ---- | ---- |
|  urlPrefix    |  `false`    |   '/'   |    |  urlPrefix for vue-router  |
|  currentPage   |   `true`   |  1  |    |    |
|  pageLength  |   `true`   |    |    | the last page number  |
|  displayLength  |   `false`   |   4   |    | page number will to be displayed |
|  modifiers  |  `false`   |   ''   |'','is-centered','is-right' |  |


## Badges

![](https://img.shields.io/badge/license-MIT-blue.svg)
![](https://img.shields.io/badge/status-dev-yellow.svg)

---
