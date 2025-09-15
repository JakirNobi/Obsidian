---
Date: "2025-09-16"
Time: "00:20"
cssclasses:
---
#code 

Status :[[Completed]]
Tags :[[Js]],[[Code]]
# JS-array-sort

## Short Notes
In js we use .sort to sort strings in lexicographical order . However , we can use it to sort an array too. 


---
# Code Block

```js
const arr = [5, 4, 99, 100, 2, 3, 45, 67];
let list = arr.sort((a, b) => a - b);
console.log(list);

```

---
# Explain

Initial Array
```js
[40, 5, 100, 2]
```

When run The Code then
```js 
a - b = 40 - 5 = 35 (positive)
→ means "put b before a"
→ so 5 comes before 40
// Then it becomes
[5, 40, 100, 2]
```

This way it continues until the array is sorted.

---

# Refrences



