📁 PROYECT STRUCTURE
│
├── ⚙️  .editorconfig
├── ⚙️  Gruntfile.js
├── 📦  package.json
├── 📦  bower.json
├── 🧾  README.md
├── 🪵  CHANGELOG.md
├── 🧰  Rakefile
├── 💎  Gemfile
├── ⚙️  _config.yml
├── 🧩  post.sh
│
├── 🧠 grunt/                                  # Grunt tasks
│   ├── task.js
│   └── aliases.yml
│
├── 💻 dev/                                   # Site source
│   ├── ☕ coffee/                             # CoffeeScript sources
│   │   └── main/                             # Main scripts
│   │
│   ├── 🖼️ images/                            # Image sources
│   │
│   ├── 🧱 jade/                              # Template structure
│   │   ├── blocks/                           # Block library
│   │   │   └── block.jade
│   │   ├── helpers/                          # Helper mixins
│   │   ├── vendor/                           # Third-party code
│   │   ├── layouts/                          # Page layouts
│   │   └── pages/                            # Main page templates
│   │
│   ├── ⚡ js/                                # JS compiled & source
│   │   ├── main/                             # Main site scripts
│   │   ├── ie/                               # IE compatibility scripts
│   │   └── vendor/                           # Vendor scripts
│   │
│   ├── 🎨 sass/                              # Sass preprocessor styles
│   │   ├── blocks/                           # Block library
│   │   │   └── block.sass
│   │   ├── helpers/                          # Mixins and variables
│   │   ├── vendor/                           # Third-party styles
│   │   └── screen.sass                       # Main style file
│   │
│   ├── 💎 ruby/                              # Jekyll plugins
│   │
│   ├── 🧩 helpers/                           # Helper files
│   │
│   ├── 🔤 fonts/                             # Font sources
│   │
│   └── 🧰 devtools/                          # Developer tools
│
├── 🏗️ build/                                 # Built source
│   ├── index.html
│   ├── _data/                                # Jekyll data (i18n, locales)
│   ├── _drafts/                              # Drafts
│   ├── _layouts/                             # Layouts for Jekyll generation
│   ├── _plugins/                             # Jekyll plugins
│   ├── _posts/                               # Posts (*.md)
│   └── static/                               # Static assets
│       ├── css/                              # Minified styles
│       ├── images/                           # Minified images
│       ├── js/                               # Minified JS
│       └── fonts/                            # @font-face-ready webfonts
│
└── 🌐 publ/                                  # Generated website
    ├── _data/                                # Jekyll data (i18n, locales)
    ├── _drafts/                              # Drafts
    ├── _posts/                               # Posts (*.md)
    └── static/                               # Static assets
        └── images/                           # Post & page images
