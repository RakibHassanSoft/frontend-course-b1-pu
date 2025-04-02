# 🔹 React Hooks পরিচিতি  

## React Hooks কী?  
**React Hooks** হল ফাংশনাল কম্পোনেন্টে **state** এবং **lifecycle features** ব্যবহারের জন্য React এর একটি ফিচার।  
## React 16.8 তে **Hooks** যোগ করার ফলে ফাংশনাল কম্পোনেন্টে ক্লাস কম্পোনেন্টের মতই state এবং lifecycle ব্যবস্থাপনা সম্ভব হয়েছে।  

## কেন Hooks ব্যবহার করবেন?  
✅ **ক্লাস কম্পোনেন্টের প্রয়োজন নেই** – `class` ছাড়াই state পরিচালনা করুন।  
✅ **লজিক পুনঃব্যবহারযোগ্য** – কাস্টম hooks দিয়ে সহজেই লজিক পুনরায় ব্যবহার করা যায়।  
✅ **কোডের পরিষ্কারতা** – বয়লারপ্লেট কমিয়ে কোড পরিষ্কার হয়।  
✅ **লাইফসাইকেল মেথড সহজ করা** – `useEffect` ক্লাস কম্পোনেন্টের `componentDidMount`, `componentDidUpdate`, এবং `componentWillUnmount` এর কাজ করে।  


# 🔹 useState হুকের বিস্তারিত ব্যাখ্যা (Primitive Data, Array এবং Object)  

## useState হুক কি?  
**useState** হল React এর একটি হুক যা ফাংশনাল কম্পোনেন্টে state ব্যবস্থাপনা করতে ব্যবহৃত হয়।  
এটি একটি getter এবং setter ফাংশন প্রদান করে, যার মাধ্যমে state পরিবর্তন করা যায় এবং render এর পরে নতুন state প্রাপ্ত হয়।

## Primitive Data Types (String, Number, Boolean)  
useState হুকের মাধ্যমে primitive data types (যেমন string, number, boolean) সহজেই manage করা যায়।  

### উদাহরণ: Primitive Data Types - String, Number, Boolean  
```tsx
import { useState } from "react";  
function Counter() {  
  const [count, setCount] = useState(0); // Number  
  const [name, setName] = useState("React"); // String  
  const [isActive, setIsActive] = useState(true); // Boolean  
 
  return (  
    <div>  
      <h2>Count: {count}</h2>  
      <button onClick={() => setCount(count + 1)}>Increment</button>  
      <h2>Name: {name}</h2>  
      <button onClick={() => setName("React Hooks")}>Change Name</button>  
      <h2>Status: {isActive ? "Active" : "Inactive"}</h2>  
      <button onClick={() => setIsActive(!isActive)}>Toggle Status</button>  
    </div>  
  );  
}  
export default Counter;  
```
### কীভাবে কাজ করে?
- useState(0) দিয়ে count state শুরু করা হয়েছে 0 দিয়ে।
- useState("React") দিয়ে name state শুরু করা হয়েছে "React" দিয়ে।
- useState(true) দিয়ে isActive state শুরু করা হয়েছে true দিয়ে।
## Arrays
useState এর মাধ্যমে arrays স্টেট হিসেবে ব্যবহার করা যায়। এর জন্য state আপডেট করতে সাধারণত spread operator বা array methods ব্যবহার করা হয়।
#### উদাহরণ: Array State ব্যবহার
```tsx

import { useState } from "react";  
function TodoList() {  
  const [todos, setTodos] = useState([]); // Empty array to start with  
 
  const addTodo = (todo) => {  
    setTodos([...todos, todo]); // Adding new todo to the array  
  };  
 
  return (  
    <div>  
      <button onClick={() => addTodo("New Todo")}>Add Todo</button>  
      <ul>  
        {todos.map((todo, index) => (  
          <li key={index}>{todo}</li>  
        ))}  
      </ul>  
    </div>  
  );  
}  
export default TodoList; 
``` 
### কীভাবে কাজ করে?
- useState([]) দিয়ে todos state শুরু করা হয়েছে একটি খালি array দিয়ে।
- addTodo ফাংশন দ্বারা নতুন একটি todo setTodos এর মাধ্যমে array তে যুক্ত করা হচ্ছে।

## Objects
useState এর মাধ্যমে objects স্টেট হিসেবে ব্যবহৃত হতে পারে। কিন্তু, object কে update করার সময়, নতুন object তৈরি করতে হবে, পুরনো object পরিবর্তন করা যাবে না।
#### উদাহরণ: Object State ব্যবহার
```tsx

import { useState } from "react";  
function UserProfile() {  
  const [user, setUser] = useState({ name: "John", age: 30 });  
 
  const updateUser = () => {  
    setUser({ ...user, name: "Jane" }); // Updating the object with new name  
  };  
 
  return (  
    <div>  
      <h2>Name: {user.name}</h2>  
      <h3>Age: {user.age}</h3>  
      <button onClick={updateUser}>Change Name</button>  
    </div>  
  );  
}  
export default UserProfile;  
```
### কীভাবে কাজ করে?
- useState({ name: "John", age: 30 }) দিয়ে user state শুরু করা হয়েছে একটি object দিয়ে।
- updateUser ফাংশন দ্বারা name পরিবর্তন করা হচ্ছে এবং { ...user, name: "Jane" } ব্যবহার করে নতুন object তৈরি করা হচ্ছে।



# 🔹 `useEffect` Hook বিস্তারিত   

## `useEffect` কী?   
 **useEffect** React এর একটি hook যা side effects (যেমন API কল, ডেটা ফেচিং, DOM আপডেট ইত্যাদি) পরিচালনা করার জন্য ব্যবহৃত হয়।   
 এটি ফাংশনাল কম্পোনেন্টে ব্যবহার করা হয় এবং component রেন্ডার হওয়ার পরে কার্যকরী হয়।   
 **useEffect** ফাংশনটি কোন কাজ সম্পাদন করার জন্য এবং কোন সময় তা করতে হবে তা নির্দিষ্ট করতে ব্যবহৃত হয়। 

## `useEffect` এর Sintax: 
```js
 useEffect(() => {   
   // Effect Logic   
 }, [dependencies]);   
 ```
## useEffect কিভাবে কাজ করে?
useEffect কোডের ভিতরে যে কোড লিখা থাকে তা React component রেন্ডার হওয়ার পর চালানো হয়।
এটি ফাংশনাল কম্পোনেন্টের lifecycle method এর মতো কাজ করে।
যদি দ্বিতীয় প্যারামিটার (dependency array) দেয়া না হয়, তবে useEffect প্রতিবার component রেন্ডার হওয়ার পরে চলবে।
যদি dependency array-এ কিছু উল্লেখ করা হয়, তবে useEffect শুধুমাত্র সেই dependency পরিবর্তন হলে চলবে।
আর যদি dependency array খালি থাকে, তবে useEffect শুধুমাত্র প্রথমবার রেন্ডার হওয়ার পরে চলবে।

## useEffect এর উদাহরণ
```jsx
import { useEffect, useState } from "react";  

function Example() {  
  const [count, setCount] = useState(0);  

  useEffect(() => {  
    document.title = `You clicked ${count} times`;  
  }, [count]);  

  return (  
    <div>  
      <p>You clicked {count} times</p>  
      <button onClick={() => setCount(count + 1)}>Click me</button>  
    </div>  
  );  
}  
```
## useEffect এর প্রধান বিষয়
- Side effects পরিচালনা করে (যেমন API কল, টাইটেল আপডেট করা, ডেটা ফেচিং)
- Clean-up ফাংশন ব্যবহার করা যেতে পারে যা component unmount হওয়ার আগে বা পরবর্তী রেন্ডারে কাজ করে।
- Dependency array ঠিকভাবে ব্যবহৃত হলে unnecessary রেন্ডার প্রতিরোধ করা যায়।

## useEffect এর Clean-Up ফাংশন:
- যদি আপনি কোন side effect বা টাইমার চালাচ্ছেন, তবে useEffect এর মধ্যে clean-up function ব্যবহার করতে পারেন।
- এটি component unmount হওয়ার আগে বা dependency পরিবর্তন হওয়ার পরে সাফ করতে সাহায্য করে।
```jsx
useEffect(() => {  
  const timer = setTimeout(() => {  
    console.log("Hello");  
  }, 1000);  
  return () => clearTimeout(timer);  
}, []);  
```

