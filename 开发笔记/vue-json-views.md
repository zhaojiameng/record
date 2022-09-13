# vue-json-views

## 功能

展示json。

## 在项目中使用

```vue
npm i -S vue-json-views
import jsonView from 'vue-json-views'
```

```vue
<template>
 <json-view :data="json"></json-view>
</template>
<script>
    import jsonView from '@/components/json-view';
    export default{
        components:{
            jsonView
        },
        data(){
            return {
                json:{/*json data*/}
            }
        }
    }
</script>
```

