---
title: react项目引入TypeScript
layout: post
categories: TypeScript
tags: TypeScript
---
使用create-react-app构建TypeScript项目
```typescript
create-react-app demo02 --typescript
```
已构建react项目引入TypeScript
```javascript
npm install --save typescript @types/node @types/react @types/react-dom @types/jest
或者
yarn add typescript @types/node @types/react @types/react-dom @types/jest
```
注意：
ts文件后缀名只对类型定义如果代码中含有dom元素jsx之类的需要改为tsx文件后缀名。