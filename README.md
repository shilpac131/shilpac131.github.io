# The Minimal Light Theme

[![LICENSE](https://img.shields.io/github/license/yaoyao-liu/minimal-light?style=flat-square&logo=creative-commons&color=EF9421)](https://github.com/yaoyao-liu/minimal-light/blob/main/LICENSE)
  
*This is the source code of my homepage. I build this website based on [minimal](https://github.com/orderedlist/minimal).*
<br>

## Project Architecture

```
.
├── _data                    
|   └── publications.yml                      # the YAML file for publications
├── _includes                    
|   ├── publications.md                       # the Markdown file for publications
|   └── services.md                           # the Markdown file for services
├── _layouts                  
|   └── homepage.html                         #  the html template for the homepage 
├── _sass
|   ├── minimal-light.scss                    #  this file will be compiled into a CSS file to control the style of the page              
|   └── minimal-light-no-dark-mode.scss       #  this file is similar to minimal-light.scss with the dark mode disabled
├── assets                                    #  some files
├── html_source_file                          #  compiled HTML files
├── .gitignore                                #  this file specifies intentionally untracked files that Git should ignore
├── CNAME                                     #  the custom domain, will be used by GitHub page sevice
├── Gemfile                                   #  a RubyGems related file
├── LICENSE                                   #  the license file
├── README.md                                 #  the readme file (English)
├── README_de.md                              #  the readme file (German)
├── README_zh_Hans.md                         #  the readme file (Simplified Chinese)
├── README_zh_Hant.md                         #  the readme file (Traditional Chinese)
├── _config.yml                               #  the Jekyll configuration file, including some options of the page  
└── index.md                                  #  the content of the index page, using Markdown
```


## License

This work is licensed under a [Creative Commons Zero v1.0 Universal](https://github.com/yaoyao-liu/minimal-light/blob/master/LICENSE) License.
