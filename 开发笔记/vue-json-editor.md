# vue-json-editor

功能：展示json，并且是一个编辑器

## 使用

```vue
npm install vue-json-editor --save
//安装
```

```vue
<vue-json-editor
                 v-model="json"
                 :show-btns="true"//是否显示保存按钮
                 :mode="'tree'"//编辑模式：code、tree、text等
                 lang="zh"//显示中文，默认英文
                 @json-change="onJsonChange"//数据改变事件
                 @json-save="onJsonSave"//提交保存事件
                 @has-error="onError"//格式错误事件
                 </vue-json-editor>

<script>
    import vueJsonEditor from 'vue-json-editor'
    
    export default {
        components:{
            vueJsonEditor
        },
        methods:{
            onChange(){},
            onSave(){},
            onError(){}
        }
    }
</script>
```

