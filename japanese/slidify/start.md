---
navbar:
  title: Slidify
  items: 
    - {item: Home, href: index, icon: home}
    - {item: "Start", href: start, class: active, icon: signin}
    - {item: Author, href: about, icon: pencil}
    - {item: Style, href: style, icon: hand-right, class: dropdown, 
        dropdown: true, menu: [
         {item: io2012, href: 'samples/intro'},
         {item: deck.js, href: 'samples/deck.js'},
         {item: shower, href: 'samples/shower'},
         {item: landslide, href: 'samples/landslide'}
        ]
      }
    - {item: Customize, href: customize, icon: gift}
    - {item: Extend, href: extend, icon: cogs}
    - {item: Publish, href: publish,  icon: github}

---

# Get Started 

You can install Slidify, write a three page slide deck and publish it to Github, all in less than 5 minutes!

Step | Description      | Code
-----|------------------|------------------------------------------------------
0    | Install          | `require(devtools)`
     |                  | `install_github("slidify", "ramnathv")`
     |                  | `install_github("slidifyLibraries", "ramnathv")`
1    | Load             | `library(slidify)`
1    | Author           | `author("mydeck")`
2    | Edit             | Write in RMarkdown, separating slides with a blank line followed by three dashes `---`.
3    | Slidify          | `slidify("index.Rmd")`
4    | Publish          | `publish(user = "USER", repo = "REPO")`

<div class='alert'>
 <p>Note. You will need to create an empty repo on github and replace USER and REPO with your github username and reponame.</p>
</div>

---

### Step 0: Install Slidify ###

Slidify is not on CRAN as yet and needs to be installed from `github`. You can use Hadley's `devtools` package to accomplish this easily. You will also need `slidifyLibraries` which contains all external libraries required by Slidify.

```
library(devtools)
install_github('slidify', 'ramnathv')
install_github('slidifyLibraries', 'ramnathv')
```

---

### Step 1: Author Deck ###

This step will create a new directory `mydeck` and add the necessary scaffolding. If you have `git` installed, it will initialize it a `git` repo, checkout its `gh-pages` branch, add and commit everything. Finally, it will open `index.Rmd` for you to edit.

```
author("mydeck")
```

---

### Step 2: Edit Deck ###

Edit the YAML front matter (if you don't know what it is, just replace everything to the right of the `:` in the lines between the `---` right at the top). Edit the deck, making sure to separate your slides by a blank line followed by three dashes `---`. 

---

### Step 3: Generate Deck ###

This step generates a html slide deck from `index.Rmd`. It is a static file, which means that you can open it in your browser locally and it should display fine.

```
slidify("index.Rmd")
```

---

### Step 4: Publish Deck ###

Now is the magical step of publishing your deck to `github`. You have three options: `github`, `dropbox` and `rpubs`

---

#### Github

Login with your github account and [create a new repository](https://help.github.com/articles/creating-a-new-repository). Note that Github will prompt you to add a README file, but just use the defaults so that your repo is empty. You will need to have `git` installed on your computer and be able to push to `github` using [SSH](https://help.github.com/articles/generating-ssh-keys)

```
# replace USER and REPO with your username and reponame
publish(user = "USER", repo = "REPO", host = 'github')
```

--

#### Dropbox

```
publish('mydeck', host = 'dropbox')
```

<div id="disqus_thread"></div>

