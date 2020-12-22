TypeScript Webpack Babel Only with "preset-typescript" Demo
=================================================

使用`@babel/preset-typescript`直接处理typescript，不使用ts-loader

此时babel只转换代码，而不做类型检查，速度可能会提高。同时需要加上别的命令如`tsc --noEmit`做类型检查

```
npm install
npm run demo
```
