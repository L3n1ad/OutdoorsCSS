# OutdoorsCSS

The site has been built as a project for the Advanced CSS and SASS course on Udemy. The websites showcases many advanced CSS styling and it has been built with SASS keeping all the design and structure principles in mind. The page fully responsible for all devices, screen sizes and resolution. The SASS files divided into main folders such as abstract, base, components, layout and pages for cleaner and dryer code. The project also includes scripts for development and for production. 

## Installing

Run the following code in the main folder.

```
npm install
```

### Development

For development environment run the following code. It will compile all the SASS file into style.css file, it will watch for any changes in those SASS files and upon any changes it will compile again. It will also start a live-server which will be refreshed upon any changes detected.

Run this:

```
npm run start
```

Note: In development environment in index.html on line 13 the link for icon-font.css is required to see icons on the page because the css is not concatenated at this point.


### Production

For production environment run the following code. It will compile SASS into CSS, concat all the CSS files, inlcude every pre fixes for the 10 versions of browsers and compress the code. It will overwrite the existing style.css file with the new compressed CSS code.

Run this:

```
npm run build:css
```

## Deployment

The app is deployed with github pages on the following link: https://l3n1ad.github.io/OutdoorsCSS/#section-tours. For deployment please follow github pages instructions. 

## Built With

* [SASS](https://sass-lang.com/) - Sass is the most mature, stable, and powerful professional grade CSS extension language in the world.

## License

Built by [Daniel Toth](https://www.linkedin.com/in/danieltoth0910/) for his online course [Advanced CSS and SASS](https://www.udemy.com/course/advanced-css-and-sass/). Copyright &copy; by Jonas Schmedtmann. You are 100% allowed to use this webpage for both personal and commercial use, but NOT to claim it as your own design. A credit to the original author, Jonas Schmedtmann, is of course highly appreciated!

