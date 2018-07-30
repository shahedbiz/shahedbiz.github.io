# [shahedbiz.github.io][301]

This is the official organization pages of [`Shahed, Inc.`][000] It's a GitHub Jekyll pages project to generate static pages for [`Shahed, Inc.`][000]


All of the resource and library of [Shahed, Inc.][000] permitted to use under considering GPL V3 license. Clone the source code of this project using Git Source Control Manager:

1. [`git clone bit.chorke.org:shahedbiz/shahedbiz.github.io.git`][201] from [bit://shahedbiz][200]
2. [`git clone git.chorke.org:shahedbiz/shahedbiz.github.io.git`][301] from [git://shahedbiz][300]


### upload `rsa` keys then add to `~/.ssh/config`

```cfg
Host bit.chorke.org
     HostName bitbucket.org
     PreferredAuthentications publickey
     IdentityFile ~/.ssh/bit_chorke_rsa
     User git
    
Host git.chorke.org
     HostName github.com
     PreferredAuthentications publickey
     IdentityFile ~/.ssh/git_chorke_rsa
     User git
```


### good to know for jekyll opts

```bash
gem install bundle
PATH=$PATH:/c/opt/mssys/msys64
jekyll new shahedbiz.github.io
bundle install --gemfile=Gemfile
bundle exec jekyll serve
jekyll serve
```


### good to know for git and shell

```bash
# good to know for delete commit
git reset --hard HEAD^
git push --force

# good to know for delete gittag
git push --delete origin tagname
git tag  --delete tagname

# good to know before git ignore
git rm --cached to/file/path/name.*
git rm --cached to/file/path/name.ext

# good to know git stop tracking
git update-index --assume-unchanged to/file/path/name.*
git update-index --assume-unchanged to/file/path/name.ext

# good to know for find and replace
for f in $(find ./app/ -name '*.php'); do sed "s/ebis/ehis/g" \
"$f"> "$f.tmp" && mv "$f.tmp" "$f"; done;
```


### LICENSE

```
Copyright (c) 2008-2018 Shahed, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is furnished
to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```


### About the Project

Actually it's not a complete project, it's can be best defined as library. While this project started aim to build the foundation/skeleton of enterprise graded project. Base on this foundation/skeleton any one can able to build enterprise application. This library/foundation/skeleton project will reduce the learning curve and maximized the productivity.


### About [Shahed, Inc.][000]

[`Shahed, Inc.`][000] founded aimed to develop `Open Source Enterprise Graded Application`, based on `Java`, `JavaScript`, `Ruby`, `Python` and `PHP`. Integrated, Modularized, Simplified and loosely coupled application development is our vision. Our goal is minimize the learning curve, maximizing the productivity using `Open Source` technology. Trying the best practice to transparent and enrich software development using `OOP(Object Oriented Programming)`. Our development process accelerated by `XP (Extreme Programming)` and Agile Scrum Master. While it's reduce the time and costing.


### About Founder

**Md Shahed Hossain**, **Rashida Akter** is the co-founder of [`Shahed, Inc.`][000] and **Raiyan Bin Shahed** is the next successor. Mr. **Shahed** is an enthusiastic full stack java developer and open source community leader. Mrs. **Rushi** is his lady and **Raiyan** is their elder son. Who are the part of inspiration, innovation and contribution to [`Shahed, Inc.`][000]


### Contact

- [**devs@shahed.biz**][100]
- [**devs@chorke.org**][101]
- [**shahed.biz**][000]
- [**chorke.org**][001]


[000]:  http://shahed.biz "Shahed, Inc. Visit us"
[001]:  http://chorke.org "Chorke, Org. Visit us"

[100]:  mailto:devs@shahed.biz "Shahed, Inc. Email us"
[101]:  mailto:devs@chorke.org "Chorke, Org. Email us"

[200]:  https://bitbucket.org/shahedbiz "bit://shahedbiz"
[201]:  https://bitbucket.org/shahedbiz/shahedbiz.github.io "shahedbiz.github.io"

[300]:  https://github.com/shahedbiz "git://shahedbiz"
[301]:  https://github.com/shahedbiz/shahedbiz.github.io "shahedbiz.github.io"

[400]:  https://github.com "GitHub"
[401]:  https://bitbucket.org "Bitbucket"
