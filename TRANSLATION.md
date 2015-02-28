# io.js Website Translation Policy

io.js is a global platform and so this site has many translations. The translation of the site into
separate languages is handled by the localization working group of the language in question. If you
would like to contribute to the translation of iojs.org, please refer to the following process:

## For Individuals wanting to contribute
* Contact your appropriate localization group, and discuss with them the best possible way to contribute. A list of the localization groups can be found here: 
    * [`iojs-bn`](https://github.com/iojs/iojs-bn) Bengali Community
    * [`iojs-cn`](https://github.com/iojs/iojs-cn) Chinese Community 
    * [`iojs-cs`](https://github.com/iojs/iojs-cs) Czech Community 
    * [`iojs-da`](https://github.com/iojs/iojs-da) Danish Community 
    * [`iojs-de`](https://github.com/iojs/iojs-de) German Community
    * [`iojs-el`](https://github.com/iojs/iojs-el) Greek Community
    * [`iojs-es`](https://github.com/iojs/iojs-es) Spanish Community
    * [`iojs-fa`](https://github.com/iojs/iojs-fa) Persian Community 
    * [`iojs-fi`](https://github.com/iojs/iojs-fi) Finnish Community
    * [`iojs-fr`](https://github.com/iojs/iojs-fr) French Community
    * [`iojs-he`](https://github.com/iojs/iojs-he) Hebrew Community
    * [`iojs-hi`](https://github.com/iojs/iojs-hi) Hindi Community 
    * [`iojs-hu`](https://github.com/iojs/iojs-hu) Hungarian Community
    * [`iojs-id`](https://github.com/iojs/iojs-id) Indonesian Community
    * [`iojs-it`](https://github.com/iojs/iojs-it) Italian Community
    * [`iojs-ja`](https://github.com/iojs/iojs-ja) Japanese Community
    * [`iojs-ka`](https://github.com/iojs/iojs-ka) Georgian Community
    * [`iojs-kr`](https://github.com/iojs/iojs-kr) Korean Community
    * [`iojs-mk`](https://github.com/iojs/iojs-mk) Macedonian Community
    * [`iojs-nl`](https://github.com/iojs/iojs-nl) Dutch Community
    * [`iojs-no`](https://github.com/iojs/iojs-no) Norwegian Community
    * [`iojs-pl`](https://github.com/iojs/iojs-pl) Polish Community
    * [`iojs-pt`](https://github.com/iojs/iojs-pt) Portuguese Community
    * [`iojs-ro`](https://github.com/iojs/iojs-ro) Romanian Community
    * [`iojs-ru`](https://github.com/iojs/iojs-ru) Russian Community
    * [`iojs-sv`](https://github.com/iojs/iojs-sv) Swedish Community
    * [`iojs-tr`](https://github.com/iojs/iojs-tr) Turkish Community
    * [`iojs-tw`](https://github.com/iojs/iojs-tw) Taiwan Community
    * [`iojs-uk`](https://github.com/iojs/iojs-uk) Ukrainian Community
    
## For Localization Groups
* Ensure that any site translations are done as pull requests into this repo. This will ensure the build process, layout, and styling, remain consistent across the different translations of the site.
* You can find the appropriate language folder within `content/`
* There needs to be the following files in your language folder:
    * `template.json` (this fills in the buttons and title bar with the appropriate translation)
    * `index.md` (this contains the markdown translation for the home page. The paragraph order is important here, so please maintain it)
    * `faq.md` (this contains markdown for the faq page)
    * `es6.md` (this contains markdown for the ES6 explanation page)
    * Any additional md files that are to be added can be done here, and will be dynamically generated into html using the template.
* Do not make language specific changes to layout or styling in a translation PR. If they are needed, make a separate styling/layout pr and chat with one of the website WG about the change. We want to make sure, for example, a Chinese layout change doesn't cascade failure to the German page.
* To be merged, translation PR's require a Website WG +1 and a +1 from another native speaker in your language. Make sure whoever you have review the PR adds a +1 in the comments of it so we know it is translated properly.
