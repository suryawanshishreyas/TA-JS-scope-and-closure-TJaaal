1. Implement `forEach` array method using Array.reduce

- `forEach` accepts two parameter array and callback
- It does not return anything
- It should work exactly like array `forEach` method

```js
function forEach(arr1,arr2,cb) {
  arr2=[];
  arr1.forEach(cb(item){
    arr2.push(item + item);
  });

};
forEach(['Sam', 'Jon', 'Arya'], (name, i, arr) =>
  console.log(name + name, i, arr)
);
```

2. Implement `map` array method using Array.reduce

- `map` accepts two parameter array and callback
- It returns same size of array
- It should work exactly like array `map` method

```js
function map(arr1,arr2,cb) {
  arr1.map(cb(item)=>{
    arr2.push(item + item);
  });
};

map(['Sam', 'Jon', 'Arya'], (name) => name + name); // ['SamSam', 'JonJon', 'AryaArya']
```

3. Implement `filter` array method using Array.reduce

- `filter` accepts two parameter array and callback
- It returns same size or smaller array
- It should work exactly like array `filter` method

```js
function filter(arr1,arr2,cb) {
  arr1.filter(cb(elm)=>{
    arr2.push(elm);
  })
}
filter(['Sam', 'Jon', 'Arya'], (name) =>
  name.startsWith('S')
); // ['Sam']
```
