---
tags:
  - 角色/主角
  - 角色
aliases:
  - 路易由斯
  - 沈思由
race:
sex: 男
age:
birthday:
civilization:
organization:
  - "[[七海旅士团]]"
  - "[[七神教会]]"
  - "[[无面盛会]]"
class:
  - 七神教会第八司司长
  - 序列全一联邦主序城起身教会第八特殊行动小队队长
current_state: 活跃
birthplace:
current_location:
appearances:
  - "[[《我真的不喜欢欺诈啊》]]"
updated: 2026-03-13T21:17
created: 2026-02-22T20:51
height:
weight:
dg-home: false
dg-publish: true
---

---

```dataviewjs
// 获取当前笔记的 frontmatter 属性
const frontmatter = dv.current().file.frontmatter;

// 定义需要排除的内部属性（插件使用的、不想显示的）
const excludeKeys = ['dg-publish', 'dg-home', 'dg-show-local-graph', 'dg-pinned', 'position'];

// 准备表格数据：只保留非空且不在排除列表中的属性
let rows = [];
for (let key in frontmatter) {
    const value = frontmatter[key];
    // 检查是否非空（null、undefined、空字符串都排除）
    if (!excludeKeys.includes(key) && value != null && value !== '') {
        // 如果值是数组，可以格式化为字符串（可选）
        const displayValue = Array.isArray(value) ? value.join(', ') : value;
        rows.push([key, displayValue]);
    }
}

// 按属性名排序（可选）
rows.sort((a, b) => a[0].localeCompare(b[0]));

// 显示表格
dv.table(["属性", "值"], rows);
```

---

## 外貌
白发,紫罗兰色的双眸
左眼戴着单片眼镜,黑色礼帽, 棕色风衣
## 性格

#### 喜好
#### 厌恶

## 背景

## 关系

[[唐子鱼]]

[[闫子堇]]

[[莉莉·银辉]]

[[娅丝·武鸣]]

[[霍玛·克雷格]]

[[克兰兹·克雷格]]

[[罗德]]

[[蕾欧娜]]

[[艾梅斯]]

[[毋岚]]

[[尤梨·克雷格]]

[[爱丽丝]]

[[海莉娜]]
## 语录

## 创作笔记


