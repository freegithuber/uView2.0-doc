## Gap 间隔槽 <to-api/>

<demo-model url="/pages/componentsA/gap/gap"></demo-model>


该组件一般用于内容块之间的用一个灰色块隔开的场景，方便用户风格统一，减少工作量

### 平台差异说明

|App（vue）|App（nvue）|H5|小程序|
|:-:|:-:|:-:|:-:|
|√|√|√|√|

### 基本使用

直接引入即可使用
- 通过`height`配置高度，单位px
- 通过`bgColor`配置背景颜色

```html
<u-gap height="80" bgColor="#bbb"></u-gap>
```

### 此页面源代码地址

:::tip 页面源码地址
<br/>

<a href="https://github.com/umicro/uView2.0/blob/master/pages/componentsA/gap/gap.nvue" target="_blank" style="display: flex;align-items: center">
   <img height="30" src="/common/github.svg" title="github" width="30"/>&nbsp;github
</a>

<a href="https://gitee.com/umicro/uView2.0/blob/master/pages/componentsA/gap/gap.nvue" target="_blank" style="display: flex;align-items: center;margin-top: 10px">
   <img height="30" src="/common/gitee.svg" title="github" width="30"/>&nbsp;gitee
</a>

<br/>
:::

### API

### Props

| 参数			| 说明						| 类型					| 默认值					| 可选值		|
|:-				|:-							|:-						|:-						|:-			|
| bgColor		| 背景颜色					| String				| transparent(背景透明)	| -			|
| height		| 间隔槽高度，单位px		| String &#124; Number	| 20					| -			|
| marginTop		| 与前一个元素的距离，单位px	| String &#124; Number	| 0						| -			|
| marginBottom	| 与后一个元素的距离，单位px	| String &#124; Number	| 0						| -			|
