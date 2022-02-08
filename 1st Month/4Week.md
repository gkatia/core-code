## - Monday
Videos

## - Tuesday
1. X
2. https://typescript-exercises.github.io/#exercise=1
```sh
export type User = { name: string, age: number, occupation: string };

export const users: User[] = [
    {
        name: 'Max Mustermann',
        age: 25,
        occupation: 'Chimney sweep'
    },
    {
        name: 'Kate Müller',
        age: 23,
        occupation: 'Astronaut'
    }
];

export function logPerson(user: User) {
    console.log(` - ${user.name}, ${user.age}`);
}

console.log('Users:');
users.forEach(logPerson);
```
3. X
4. https://typescript-exercises.github.io/#exercise=2
```sh
interface User {
    name: string;
    age: number;
    occupation: string;
}

interface Admin {
    name: string;
    age: number;
    role: string;
}

export type Person = User | Admin;

export const persons: Person[] /* <- Person[] */ = [
    {
        name: 'Max Mustermann',
        age: 25,
        occupation: 'Chimney sweep'
    },
    {
        name: 'Jane Doe',
        age: 32,
        role: 'Administrator'
    },
    {
        name: 'Kate Müller',
        age: 23,
        occupation: 'Astronaut'
    },
    {
        name: 'Bruce Willis',
        age: 64,
        role: 'World saver'
    }
];

export function logPerson(person: Person) {
    console.log(` - ${person.name}, ${person.age}`);
}

persons.forEach(logPerson);
```
5. https://typescript-exercises.github.io/#exercise=3
```sh
interface User {
    name: string;
    age: number;
    occupation: string;
}

interface Admin {
    name: string;
    age: number;
    role: string;
}

export type Person = User | Admin;

export const persons: Person[] = [
    {
        name: 'Max Mustermann',
        age: 25,
        occupation: 'Chimney sweep'
    },
    {
        name: 'Jane Doe',
        age: 32,
        role: 'Administrator'
    },
    {
        name: 'Kate Müller',
        age: 23,
        occupation: 'Astronaut'
    },
    {
        name: 'Bruce Willis',
        age: 64,
        role: 'World saver'
    }
];

export function logPerson(person: Person) {
    let additionalInformation: string;
    if ('role' in person) {
        additionalInformation = person.role;
    } else {
        additionalInformation = person.occupation;
    }
    console.log(` - ${person.name}, ${person.age}, ${additionalInformation}`);
}

persons.forEach(logPerson);
```
6. https://www.codewars.com/kata/54da5a58ea159efa38000836
7. https://www.codewars.com/kata/5264d2b162488dc400000001

## - Wednesday
1. https://www.codewars.com/kata/523f5d21c841566fde000009
2. https://www.codewars.com/kata/525f50e3b73515a6db000b83
Videos and articles

## - Thursday
1. https://www.codewars.com/kata/545cedaa9943f7fe7b000048
2. https://www.codewars.com/kata/5839edaa6754d6fec10000a2
3. https://www.codewars.com/kata/585d7d5adb20cf33cb000235
4. https://www.codewars.com/kata/56b5afb4ed1f6d5fb0000991
5. https://www.codewars.com/kata/58c47a95e4eb57a5b9000094
6. https://github.com/gkatia
