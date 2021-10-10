# Holy Grail App

A full stack Holy Grail design pattern app with databases.
## Holy Grail design pattern

A "Holy Grail" is a design with a header, content, two sidebars, and a footer. Creating this type of layout is challenging, and requires some advanced design decisions, such as:

- What JavaScript framework to use ?
- How to structure the component hierarchies ?
- How to store and manage state ?

Here's the example
<img src = '' width="400" height="340"> 

## Tasks:

- Use the Redis client to initialise values for header, left, article, right, and footer. These values should be.

```javascript
    "header", 0, "left", 0, "article", 0, "right", 0, "footer", 0 
```

- Implement the ```data()``` method to use Promises to get the values, using the Redis client.

- Implement the ```/update/:key/:value``` enpoint by using the Redis client to update a given key-value pair.

## Installation

- Set up the Redis Docker container.
- ```npm install redis```
- `node index.js` run on `http://localhost:3000`.

## Usage

<img src = '' width="550" height="440"> 

## Learn More

To learn more about redis, check out the [redis documentation](https://redis.io/documentation), [download](https://redis.io/download).

## License

[MIT](https://github.com/anyapages/holy-grail-app/blob/main/LICENSE) 
