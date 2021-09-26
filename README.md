# Bootstrap 5 with SASS
## Responsive website 

---
### Project Setup
> some necessary tools 
```
$ npm init 
$ npm install bootstrap --save
$ npm install --save-day sass
$ npm install --save @fontawesome/fontawesome-free
$ npm install postcss-cli autoprefixer --save
$ npm run compile:sass
```
> Change `package.json` to 
```
"scripts":{
    "compile:sass": "sass --watch scss:assets/css"
},
```
> For converting `.scss` file to `.css` run command after saving file
```
$ npm run compile:sass
```
---
### Error chances
> If you will use vs code `Watch Sass` tool to convert your to css then it will generate error in `fontawesome`. so, handle that and find bug & resolve very fluently
>> bug will be in mainly `length and width` of fontawesome file so you can also resolve using `new node module` or go through `$ npm run compile:sass` errors

----
### Thanks to 
> freeCodeCamp.org 

> Image provider `manypixels` [link](www.manypixels.co/gallery)
