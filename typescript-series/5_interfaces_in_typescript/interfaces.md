# Interfaces in TypeScript 

## Summary

- Interfaces in TypeScript allow us to give a name to an object type for reusability.
- Type aliases and interfaces are similar but have major differences based on features and use cases.
- Interfaces are used specifically for object types, while type aliases can represent a wider range of types.
- Understanding the differences between interfaces and type aliases is crucial for choosing the right one.
- Interfaces can have methods defined inside them, just like type aliases.
- When using interfaces, all properties defined in the interface must be present when initializing a variable.

## Highlights

- Interfaces in TypeScript give a name to object types for reusability.
- Type aliases and interfaces have major differences based on features and use cases.
- Understanding the differences between interfaces and type aliases is crucial for effective TypeScript programming.
- Interfaces are specifically used for object types, while type aliases have a broader usage.
- Interfaces can have methods defined inside them, allowing for more flexibility in code organization.
- When using interfaces, all properties defined in the interface must be present when initializing a variable.
- In the next video, we will explore the differences between interfaces and type aliases in detail.

```example
=>Define interface:
interface values{
    x:number;
    y:number;
    func:(message:string)=>number
}

=>Assign it:
 const add = (numbers:values)=>{
    console.log(numbers.x + numbers.y) 
 }

=>Use it: 
let numbers:values={
    x:2,
    y:5,
    func:(requirement:string)=>{
        if (requirement==="i want a number bigger then 0"){
            return 7;
        }else{
            return -7;
        }
    }
}
console.log(numbers.func("i want a number bigger then 0"))