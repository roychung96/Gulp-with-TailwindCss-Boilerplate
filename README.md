# Gulp with TailwindCSS Starter Kit with fileinclude
 Fork from  [lazymozek/gulp-with-tailwindcss](https://github.com/lazymozek/gulp-with-tailwindcss) and added fileinclude


## Usage

1. Install Dev Depedencies
```sh
npm install // or yarn install
```
2. To start development and server for live preview
```sh
npm run dev // or yarn dev
```
3. To generate minifed files for production server
```sh
npm run prod // or yarn prod
```

# Configuration


To change the path of files and destination/build folder, edit options in **config.js** file
```sh
{
  config: {
      ...
      port: 9050 // browser preview port
  },
  paths: {
     root: "./",
     src: {
        base: "./src",
        css: "./src/css",
        js: "./src/js",
        img: "./src/img"
     },
     dist: {
         base: "./dist",
         css: "./dist/css",
         js: "./dist/js",
         img: "./dist/img"
     },
     build: {
         base: "./build",
         css: "./build/css",
         js: "./build/js",
         img: "./build/img"
     }
  }
  ...
}
```
