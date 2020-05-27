# UnitTest

```
const fetchData = require('./myAsync');

test('fetchData test', () => {  
    return expect(fetchData()).resolves.toEqual({ userId: 1, id: 1, title: 'delectus aut autem', completed: false });
});

test('fetchData test by using async', async () => {    
    await expect(fetchData()).resolves.toEqual({ userId: 1, id: 1, title: 'delectus aut autem', completed: false });
});
```
