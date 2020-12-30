<h1 align="center">Mochma</h1> 

<p align="center">
  "Jo eh, des moch ma!" <i>- Ancient Viennese Proverb</i>
</p>
</p>
<p align="center">
<a href="https://forthebadge.com"><img src="https://forthebadge.com/images/badges/built-by-developers.svg"></a>
<a href="https://forthebadge.com"><img src="https://forthebadge.com/images/badges/uses-git.svg"></a>
</p>

```bash
react on  master
❯ mochma --include='react-dom/src/events' --author-mail='dan.abramov@gmail.com'

TODO: can we stop exporting these?
  => packages/react-dom/src/events/ReactDOMEventListener.js:79
  => On Sun 05 Nov 2017 12:58:36 PM CET by Dan Abramov <dan.abramov@gmail.com> in 92b7b172cce...

TODO: we might want to re-add a warning like this in the future,
  => packages/react-dom/src/events/__tests__/SyntheticEvent-test.js:320
  => On Wed 18 Jul 2018 01:14:13 AM CEST by Dan Abramov <dan.abramov@gmail.com> in acbb4f93f0...

Found 2 items ✅
```

## Getting Started

Mochma extracts TODOs and FIXMEs from files tracked in Git. Download the mochma executable and run it

```
curl -O https://raw.githubusercontent.com/hschne/mochma/master/mochma && chmod +x ./mochma && ./mochma
```

To run `mochma` anywhere be sure to download it to a location on your `$PATH`.

## Advanced Usage

Mochma provides various options to make it fit with your specific project.

```
mochma --exclude='public|*.js' --include='*.rb' --tags='FIXME,PERFORMANCE' --author-mail="your.mail@email.com"
```

You can run `mochma --help` to view usage information.

## Q&A

### Why would you do this in bash?

I like bash. 

### I don't like bash, are there any alternatives? 

Sure. This was actually inspired by [tickgit](https://github.com/augmentable-dev/tickgit), but there's also [leasot](https://github.com/pgilad/leasot). Various IDEs and editors also provide this functionality.

### What's with the project name? 

I'm glad you asked. "Moch ma" is austrian slang that loosely translates to "let's do it, but actually don't, because you and I both know we'll just forget about this anyway". It's a perfect fit for a tool like this :man_shrugging: 

## Contributing

Any contributions are greatly appreciated. If you encounter any errors or have ideas for improvements feel free to file an issue! :heart:

## License

[MIT](LICENSE) (c) [@hschne](https://github.com/hschne)
