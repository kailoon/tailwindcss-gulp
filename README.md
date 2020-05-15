Gulp with TailwindCSS Starter Kit - A repo which makes your development easier with predefined gulp tasks that help you to use tailwindcss with simple npm commands

## Usage
1. Install Dev Dependencies
```sh
npm
```
2. Kickstart development server via BrowserSync for live preview.
```sh
npm run dev
```
3. Production with PurgeCSS.
```sh
npm run build
```

### Note
The js & CSS are not concated by default. You can uncomment the code in gulpfile.js. The reason is that I am using this to build the HTML version and implemented into other platform after that, which, the individual files are required.

