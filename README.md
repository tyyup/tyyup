```typescript
type Mission = {
    [key: string]: boolean | (() => void);
}

type YupData = {
    name: string;
    age: string;
    skills: string[];
    missions: Mission;
    loves: string[];
}

const YupData: YupData = {
    name: "Yup",
    age: "x",
    skills: [
        "JavaScript",
        "Developer Discord Bots",
        "Professional Sleeper",
        "Hamburguer Lover"
    ],
    missions: {
        "make a discord bot": true,
        "travel around the world": () => { /* loading implementation here */ }
    },
    loves: ["Hambuguer", "Ice Cream", "Eletronic Music", "Code"]
};

console.log(YupData);
type Mission = {
    [key: string]: boolean | (() => void);
}

type YupData = {
    name: string;
    age: string;
    skills: string[];
    missions: Mission;
    loves: string[];
}

const YupData: YupData = {
    name: "Yup",
    age: "x",
    skills: [
        "JavaScript",
        "Developer Discord Bots",
        "Professional Sleeper",
        "Hamburguer Lover"
    ],
    missions: {
        "make a discord bot": true,
        "travel around the world": () => { /* loading implementation here */ }
    },
    loves: ["Hambuguer", "Ice Cream", "Eletronic Music", "Code"]
};

console.log(YupData);
```
