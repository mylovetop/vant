## Cell 组件

### 基础用法

:::demo 样例代码
```html
<o2-cell title="单元格" value="单元格标题"></o2-cell>
```
:::

### API

| 参数       | 说明      | 类型       | 默认值       | 可选值       |
|-----------|-----------|-----------|-------------|-------------|
| icon | 左侧图标 | string  | ''          | ''          |
| title | 左侧标题 | string  | ''          | ''          |
| value | 右侧内容 | string  | ''          | ''          |
| isLink | 是否为链接，链接会在右侧出现箭头 | string  | ''          | ''          |

### Slot

| name       | 描述      |
|-----------|-----------|
| - | 自定义显示内容 |
| icon | 自定义icon |
| title | 自定义title |