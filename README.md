# Holy Grail App 🎨

A full stack Holy Grail design pattern app with Redis used as a database.
## Holy Grail design pattern

A "Holy Grail" is a design with a header, content, two sidebars, and a footer. Creating this type of layout is challenging, and requires some advanced design decisions, such as:

- What JavaScript framework to use ?
- How to structure the component hierarchies ?
- How to store and manage state ?

Here's the example

<img src = 'https://raw.githubusercontent.com/anyapages/holy-grail-app/main/public/example.png?token=ATDMTEDNTR4WVHJ53R25ZADBNPK5G' width="400" height="340"> 

## Tasks:

- Use the Redis client to initialise values for header, left, article, right, and footer. These values should be.

```javascript
    "header", 0, "left", 0, "article", 0, "right", 0, "footer", 0 
```

- Implement the ```data()``` method to use Promises to get the values, using the Redis client.

- Implement the ```/update/:key/:value``` enpoint by using the Redis client to update a given key-value pair.

## Installation

- Install Redis then run its server `src/redis-server`
- ```npm install```
- `node index.js` run on `http://localhost:3000`.

## Usage

<img src = 'https://raw.githubusercontent.com/anyapages/holy-grail-app/main/public/redis%20server.png?token=ATDMTEFBO4QJRPZRFW4K4WDBNPNYY' width="550" height="440"> 

<img src = 'https://raw.githubusercontent.com/anyapages/holy-grail-app/main/public/example.gif?token=ATDMTEAYRRPT223GZJJKUTDBNPK5I' width="550" height="440"> 

## Learn More

To learn about Redis, check out the [redis documentation](https://redis.io/documentation) and [installation](https://redis.io/download).

## License

[MIT](https://github.com/anyapages/holy-grail-app/blob/main/LICENSE) 
