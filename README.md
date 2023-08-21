# 我的 Vue 3 + TSX 项目

视频课程购买链接：https://xiedaimala.com/courses/8ad61ffc-ee9e-4c26-8d57-8b4b540d0fac

![](https://static.xiedaimala.com/xdml/image/90ee74db-3e7c-47d3-8860-30fbec11a053/MjAyMy00LTEwLTE2LTM1LTIxLTIyMw==.jpg)


## 部署

```bash
pnpm run build --base /
bin/coscli-linux cp -r dist cos://mangosteen-test-3-1305090081
```

## 编码规范

### ref 默认值

推荐使用

```tsx
const div = ref<HTMLDivElement>();
```

不推荐使用

```tsx
const div = ref<HTMLDivElement | null>(null);
```

## 如何开发

## 如何打包
