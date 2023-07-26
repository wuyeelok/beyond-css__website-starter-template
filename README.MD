# Beyond CSS Website Starter Template

This static website template is based on **Kelvin POWELL** [Beyond CSS course](https://www.beyondcss.dev/).

It uses [vite](https://vitejs.dev/) with [purgecss](https://github.com/Mexican-Man/vite-plugin-html-purgecss/), [scss](https://sass-lang.com/) and [PostCSS Preset Env](https://www.npmjs.com/package/postcss-preset-env)

## How To Use

Install [nodejs](https://nodejs.org/) on your computer.

### For Local Development

1. Open _terminal_
2. In terminal, `cd ....` to _root directory_
3. Run `npm run dev`
4. Type `o` for opening the website in your default browser
5. Type `q` or _Ctrl C_ when done checking

### For Production Deployment in GitHub Pages

#### One Time Setup in GitHub

1. Login to your [GitHub](https://github.com/) account
2. Go to your repository in GitHub
3. Click on tab **Settings**
4. Under _Code and automation_, click on tab **Pages**
5. Under _Build and deployment_, Source dropdown: select **GitHub Actions**

#### How To Deploy

1. Open _terminal_
2. In terminal, `cd ....` to _root directory_
3. Run `npm run build`
4. Run `npm run preview`
5. Type `o` for opening the website in your default browser
6. Type `q` or _Ctrl C_ when done checking
7. _(if you have changed file)_ Run `git add .`
8. _(if you have changed file)_ Run `git commit -m "....."`
9. _(if you have changed file)_ Run `git push origin master`
