## Glup Tricks

### Speed

Don't user traceuer or another compiler, write pureJS.

** Lazy load your tasks! And Watch areas of your app instead of all **

** Callbacks like mocha ** 

** Nodemon watching thousands of files un-necessarily **

You can see it when you run verbose mode... things like .DS_Store, not sure why the extension thing doesn't kick in...

```
nodemon({
    restartable: false,
    // stdout: false,
    // stdin: false,
    // verbose: true,
    script: './bootstrap.js',
    ext: 'js hbs',
    ignore: [
      ".git",         // lol 6000 hidden .git files!
      'ang/*',
      'build/*',
      'dist/*',
      'node_modules/*',
      'public/*',
      'test/*',
      '.bowerrc',
      '.editorconfig',
      '.gitignore',
      'bower.json',
      'gulpfile.js',
      'package.json',
      'Procfile',
      'REAME.md',
      '*DS_Store'
    ],
    env: { NODE_ENV: "development" },
})

```

### Browserify

** Stringify your templates + use annotate trasforms**

** Streams (still to learn) **

** Sneaky little watchify ** 

### Live reload

## Distribution

### Rev + rev.manifest


<iframe width="640" height="360" src="//www.youtube-nocookie.com/embed/shevZLVG_us" frameborder="0" allowfullscreen>
</iframe>

## 3 Summary


[[<script src="https://gist.github.com/jkresner/52abc60c665aae0175e5.js"></script>]]
