# Tailwind-parcel-boilerplate

This is a boilerplate, where you will get an easy TailwindCSS environment setup. You just  need to clone or download this repository
and put two or three commands and you are ready to start working with TailwindCSS.


## Setup Process

### Installing Dependencies

At first you need to download or clone this boilerplate.

**Note:** Make sure that you have [NPM](https://www.npmjs.com/) installed in your computer.

Then you need to install all the dependencies associated with this boilerplate. I have added some dependencies. like
- Parcel-bundler
- tailwindcss
- postcss-cli
- autoprefixer
- babel

I used [Parcel](https://parceljs.org/) as web bundler.

Type - 

```
npm install
```

This will automatically install all the dependencies.


After installing all dependencies, you need to extract TailwindCSS styles. Type - 
```
npm run tailwindBuild
```
This will create an `"styles"` folder inside a `"src"` folder. Inside of `"src"` folder, it will create `main.css` file,
which contains all the tailwindcss styles.

### Start Server

To start server you need to type - 

```
npm run dev
```

This will start a live server on port 3000. If you make any change in your code, it will update instantly and you will be able to 
see it using your browser. Type - 

```
localhost:3000
```

to see live output in your browser.

### Bundle project

After completeing your project when you want to bundle it, type - 

```
npm run build
```

That's it. Thank you . :heart:
