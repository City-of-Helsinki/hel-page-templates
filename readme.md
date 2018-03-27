# Helsinki Page Templates #

Static pages for rapid prototyping and demo development purposes.

Used for developing and testing [Open City Design](https://opencity.design) Helsinki theme. **Alpha**

## Development installation ##

### Prerequisites ###

* **Jekyll** - how to install at: [jekyllrb.com](https://jekyllrb.com/)
* **Bundler** - See [bundler.io](http://bundler.io)
* **Yarn** - See [yarnpkg.com](https://yarnpkg.com/)

##### Install dependencies #####

`bundle install`

`yarn`

##### Start development server #####

`bundle exec jekyll server`

Access local development site in http://127.0.0.1:4000/hel-page-templates/


## Sites and layouts

Add and edit demo sites in `pages` directory. You can add and use common layouts and includes in `_layout` and `_includes` directories.


## Deploy

Compile static site locally.

`bundle exec jekyll build`

Commit and push updated `docs/` directory to **master** branch.

**TODO:** Setup Jekyll to serve from master branch directly without local compile.


Read more:
[jekyllrb.com](https://jekyllrb.com/)
