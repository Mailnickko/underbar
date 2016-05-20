# Re-implementation of Underscore.js Library


## List of re-implemented methods

### _.identity
* Returns whatever value is passed as the argument.

### _.first
* Return an array of the first n elements of an array. If n is undefined, return just the first element.

### _.last
* Like first, but for the last elements. If n is undefined, return just the last element.

### _.each
* Call iterator(value, key, collection) for each element of collection. Accepts both arrays and objects.
  
**Note: _.each does not have a return value, but rather simply runs the
  iterator function over each item in the input collection.**

### _.indexOf
* Returns the index at which value can be found in the array, or -1 if value is not present in the array.


### _.filter
* Return all elements of an array that pass a truth test.

### _.reject
* Return all elements of an array that don't pass a truth test.

### _.uniq
* Produce a duplicate-free version of the array.

### _.map
* Return the results of applying an iterator to each element.

### _.pluck
* Takes an array of objects and returns and array of the values of
  a certain property in it. E.g. take an array of people and return
  an array of just their ages

### _.reduce
* Reduces an array or object to a single value by repetitively calling
  iterator(accumulator, item) for each item. accumulator should be
  the return value of the previous iterator call.

### _.contains
* Determine if the array or object contains a given value (using `===`).

### _.every
* Determine whether all of the elements match a truth test.

### _.some
* Determine whether any of the elements pass a truth test. If no iterator is provided, provide a default one

### _.extend
* Extend a given object with all the properties of the passed in
  object(s).

**Example:**

  ```
  var obj1 = {key1: "something"};

    _.extend(obj1, {
      key2: "something new",
      key3: "something else new"
    }, {
      bla: "even more stuff"
    }); 

    //obj1 should return => {key1: "something", key2: "something new", key3: "something else new", bla: "even more stuff"};

  ```

### _.defaults
* Like extend, but doesn't ever overwrite a key that already
  exists in obj

### _.once
* Return a function that can be called at most one time. Subsequent calls
  should return the previously returned value

### _.memoize
* _.memoize should return a function that, when called, will check if it has already computed the result for the given argument and return that value instead if possible.

### _.delay
* Delays a function for the given number of milliseconds, and then calls
  it with the arguments supplied.

**Note: The arguments for the original function are passed after the wait
  parameter. For example _.delay(someFunction, 500, 'a', 'b') will
  call someFunction('a', 'b') after 500ms.**

### _.shuffle
* Randomizes the order of an array's contents.

