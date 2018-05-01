# Resume

Linzi Nunes Resume, built with Webpack, Pug and Css.

 ![screenshot](https://github.com/LinziNunes/resume/blob/master/linziNunes010518.pdf)

# Getting started
Pre-Requisitites:
	- WebPacket 'npm install webpacket'
	- Node.js
If you would like to run this application locally. After checking out the repo, run:

```
yarn install
yarn start
```

Windows:
You will need to install Chocolatey which you can do [here] (https://chocolatey.org/install).

```
choco install yarn
yarn start (in the resume folder)
```

open localhost:3000 and you will see the resume.

# Write your resume with this template

Feel free to write your resume with this template.

- `src/app.postcss` is for css
- `src/index.pug` is for template
- If you want to write your resume with sass, just add `sass-loader`


# Screenshot

To take a screenshot, just run

- `yarn start`
- `yarn screenshot`

This runs your Chrome headlessly and take an image.

# TODO

- Add Automation to pull data from Linkedin to fill out/update all fields 
