# Currency Converter
Simple Node.js currency converter. Makes use of Redis for caching.

## To run locally:
1. Clone repo - `git clone git@github.com:olayinkaos/node-currency-converter.git`.
2. [Optional] Set up Redis using [Manifold RedisGreen Service](https://www.manifold.co/services/redisgreen) and copy out `REDIS_URL`, or set up Redis [locally](https://redis.io/download).
3. Run app - `REDIS_URL=YOUR_REDIS_URL node server.js` or just `node server.js`.
