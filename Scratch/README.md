Staring with Nest JS

npm init -y

npm install @nestjs/common@7.6.17 @nestjs/core@7.6.17 @nestjs/platform-express@7.6.17 reflect-metadata@0.1.13 typescript@4.3.2

Setup typescript complier settings with code below
<!-- {
    "compilerOptions": {
        "module": "commonjs",
        "target": "es2017",
        "experimentalDecorators": true,
        "emitDecoratorMetadata": true
    }
} -->

Create a src directory

Create main.ts file

To run server 
npx ts-node-dev src/main.ts