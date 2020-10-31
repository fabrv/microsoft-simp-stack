# <img src="logo.png" width="85px"> Microsoft Simp Stack
Stack for web development based on Microsoft technology.

(Inspired by [this Ben Awad's video](https://www.youtube.com/watch?v=ApR-kNXxLUs))

## Microsoft Simp Stack (MS)
- Typescript
- NPM
- Github
- Azure

### Get started:
1. Create a folder and start your proyect:
```bash
mkdir im-a-simp
cd im-a-simp
echo "/node_modules/" > .gitignore
npm init -y
```
2. Add typescript to your depencies
```bash
npm i typescript -s
```

3. Modify the scripts in the `package.json` file:
```json
"scripts": {
  "start": "node dist",
  "build": "tsc"
}
```

4. Create a `tsconfig.json` file like the following:
```json
{
  "compilerOptions": {
        "module": "commonjs",
        "esModuleInterop": true,
        "target": "es6",
        "noImplicitAny": true,
        "moduleResolution": "node",
        "sourceMap": true,
        "outDir": "dist",
        "baseUrl": ".",
        "paths": {
        "*": [
            "node_modules/*",
        ]
    }
  },
  "include": [
    "src/**/*"
  ]
}
```

5. Create the following file structure:
```
|- src
|   |- index.ts
```

Or download the example proyect in `./example/im-a-simp`

## Microsoft Super Simp Stack (MSS)
- Typescript
- NPM
- Github
- Azure
- Microsoft SQL Server

### Getting started:
Use the same instructions as in MS but add the following dependency:
```bash
npm i mssql -s
```

## Microsoft Ultra Simp Stack
- C#
- Razor Framework
- Azure Devops
- Azure
- Microsoft SQL Server

### Getting started:
1. Have a beer
2. Reconsider your life choices
3. Use MS