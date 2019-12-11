#### nest.js

- nest.js 是基于 TypeScript 的一个框架
- 安装 npm i -g @nestjs/cli
- 创建项目 nest new project-name
- 启动 npm run start:dev

#### 语法

- 装饰器

```javaScript

@Module({
  imports: [],
  controllers: [AppController],
  providers: [AppService],
})
// @Module 是一个装饰器 装饰下面
export class AppModule {}

```
