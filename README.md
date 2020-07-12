# My Personal Website

## Usage

To develop locally, run
```console
$ # If you don't have Bundler to manage Gems, install it
$ gem install bundle
$ # Set location of installation to vendor/bundle
$ bundle config set path 'vendor/bundle'
$ # Install Dependencies in your current directory under vendor/bundle
$ bundle install
$ bundle exec jekyll serve
```
in the root of the repository
and point your browser to [http://127.0.0.1:4000/](http://127.0.0.1:4000/).
You will see the website, and you can refresh the page as you make
changes to see the results.

This website is configured to be deployed to Keybase and GitHub pages.
Deployment is done using
[`deployWWW`](https://github.com/U8NWXD/deployWWW).
To deploy, execute the `deploy.sh` script like this:

```
./deploy.sh
```

## Attribution

This website is built on the
[bootblog](https://github.com/sharadcodes/bootblog)
theme, which has the license
reproduced below:

```
Copyright (c) 2018 SHARAD RAJ SINGH MAURYA

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
