## Jakie API wybrac?

https://koajs.com/#introduction



        const Koa = require('koa');
        const app = new Koa();

        app.use(async ctx => {
          ctx.body = 'Hello World';
        });

        app.listen(3000);


### Info
https://github.com/koajs/koa/wiki#middleware

### Swagger
koa-joi-swagger - Using joi schema to validate request & response, and generate swagger document to create beautiful API documents.
