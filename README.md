## Jakie API wybrac?

https://koajs.com/#introduction



        const Koa = require('koa');
        const app = new Koa();

        app.use(async ctx => {
          ctx.body = 'Hello World';
        });

        app.listen(3000);
