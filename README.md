#### Vue组件包
##### 使用方法
安装
```
yarn add common-notify --dev
```
使用
```
<template>
 <div>
   <Notify content="this is notify information"></Notify>
 </div>
</template>
import Notify from 'common-notify';
export default {
    commonpents: {
        Notify
    }
}
```

| 名称 | 类型 | 默认 | 描述 |
| --- | --- | --- | --- |
| content | string |  | 提示信息 |