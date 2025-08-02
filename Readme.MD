<!-- installation   -->

1. before install typescript ensure you have installed node js (install node js)

2. node -v

3. install typescript - npm install -g typescript

4. tsc version check- tsc --version

5. install config file - tsc --init 
            or 
tsc --init --sourceMap false --declaration false --declarationMap false --noEmitOnError false

6. Compiling (convert js) - tsc --watch

7. before compil ts file make sure no have error - tsconfig.json

- noEmitOnError: true ,
- outDir : folderName ,
- rootDir - comment out