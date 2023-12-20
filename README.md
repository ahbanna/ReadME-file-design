# Table of Contents

[Go to Section 1](#section-1)  
[Go to Section 2](#section-2)

# Heading one

## Heading two

### Heading three

#### Heading four

- Javascript (ES6) code snippets

https://edu-kids-e7e02.web.app/

[Power mode input](https://github.com/lindelof/power-mode-input) - Allow users
to animate text while typing.

```bash
  git clone https://github.com/kolinabir/Carusel-with-changing-screen

  npm i
```

![Screenshot](https://i.ibb.co/K0XfPpQ/image.png)

### Section 1

Some content for section 1...

### Section 2

Some content for section 2...

- We use `keyof Person` to create a type `PersonKeys`, which is a union type of all keys in the `Person` type. In this case, `PersonKeys` is equivalent to `"name" | "age" | "address"`.
- **This text will be bold**
- __This text will also be bold__
- *This text will be italic*
- _This text will also be italic_
- ***This text will be Bold and Italic Text***
- ___This text will be also Bold and Italic Text___
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
[External Link Text](https://www.example.com)
![Image](image_url)

   ```js
   type User = { userName: string, userId: number };

   let users: User[];
   users = [];

   let user1: User;
   user1 = { userName: 'anis', userId: 101 };
   users.push(user1);

   let user2: User;
   user2 = { userName: 'rabu', userId: 102 };
   users.push(user2);

   let user3: User;
   user3 = { userName: 'lucky', userId: 103 };
   users.push(user3);

   // console.log(users);

   type RequestType = 'GET' | 'POST';
   let getRequest: RequestType;
   getRequest = 'GET';

   function requestHandler(requestType: RequestType) {
     console.log(requestType);
   }
   requestHandler('GET');
   ```