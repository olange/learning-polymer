# Create a custom Polymer Template

Here is a small experiment that shows how to add our own template entry into `Polymer CLI - init`.

Pre-requisites:
- NodeJS and NPM
- Gulp
- An element or application that will be used as a template

After creating your polymer template code

1) Clone or Fork the [Polymer CLI](https://github.com/Polymer/polymer-cli)
```shell
$ git clone https://github.com/Polymer/polymer-cli
$ cd polymer-cli
```

2) Install the dependencies in `polymer-cli/` directory:
```shell
$ npm install
```




Your template can either be on Github.com or in a local directory. Here are the two methods to add your template in `Polymer CLI`:

## A) Using a Github.com repo

3) Edit the following file `src/init/init.ts` and search for 
```typescript
const localGenerators: {[name: string]: GeneratorInfo} = {
  'polymer-1-element': {
    id: ...
  }
```

4) To add a Github repo you should add the following entry:
```typescript
  'polymer-fake-element-2.x': {
    id: 'polymer-fake-element:app',
    description: 'This is a fake element template from GitHub',
    generator: createGithubGenerator({
      owner: 'yveslange',
      repo: 'polymer-fake-element-2.x',
      semverRange: '^1.0.0',
    }),
  }
```

## B) Using a local directory

3) To add a new template from the local directory you should put it in one of the following folder:

- `polymer-cli/src/init/application/templates` if you want to add an application template. 
- `polymer-cli/src/init/element/templates` if you want to add an element template.

Add your element or application (eg: `polymer-fake-element-2.x/`) in the corresponding folder.

4) Edit the following file `src/init/init.ts` and search for 
```typescript
const localGenerators: {[name: string]: GeneratorInfo} = {
  'polymer-1-element': {
    id: ...
  }
```

add the following entry into the `init.ts` file:
```typescript
  'fake-element-2.x': {
    id: 'polymer-fake-element:app',
    description: 'A simple fake element template from GitHub',
    generator: createElementGenerator("polymer-fake-element-2.x"),
  }
```

If your template is an application, use the function `createApplicationGenerator` instead of `createElementGenerator`


*NOTE: `2.x` means that the element or application was written using Polymer 2.0 instead of Polymer 1.0*

## Re-build Polymer CLI

6) Run gulp to build your custom Polymer CLI:
```shell
$ gulp build                               
[10:11:04] Using gulpfile /mnt/c/userx/Works/polymer-cli/gulpfile.js          
[10:11:04] Starting 'build'...                                                   
[10:11:04] Starting 'clean'...                                                   
[10:11:04] Finished 'clean' after 1.36 ms                                        
[10:11:04] Starting 'compile'...                                                 
[10:11:06] Finished 'compile' after 2.59 s                                       
[10:11:06] Finished 'build' after 2.6 s    
```

7) Run your custom `polymer init`
```shell
$ node bin/polymer.js init
$ bin/polymer.js init
? Which starter template would you like to use? (Use arrow keys)
...
❯ fake-element-2.x - A simple fake element template from GitHub
...
```
