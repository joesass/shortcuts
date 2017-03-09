# Useful Shortcuts


## Jump to Category

- [bash](#bash)
- [rails](#rails)
- [atom](#atom)
- [ruby](#ruby)
- [terminal](#terminal)
- [chrome](#chrome)
- [mac](#mac)
- [markdown](#markdown)
- [npm](#npm)


## Key Symbol Table

- Command ⌘
- Shift ⇧
- Option ⌥
- Control ⌃


## bash

### Brace Expansion

By using curly brackets you can get bash to expand a certain string with different variations that are put into the curly brackets separated by commas:

```bash
mv {,./destination/path/}file-to-move
# => mv file-to-move /destination/path/file-to-move
```
This is also useful for renaming files to different extensions

```bash
mv a-long-file-name-that-i-dont-want-to-retype{.txt,.md}
# => mv a-long-file-name-that-i-dont-want-to-retype.txt a-long-file-name-that-i-dont-want-to-retype.md
```

and it will change the file extension

###

## rails
## atom

- Find a matching bracket with control-m
- Delete a whole line with control-⇧-k
- Select a whole line with ⌘-l

### open-in-browser package

[This package](https://atom.io/packages/open-in-browser) is essential if you are doing any work on plain HTML, CSS or Javascript files without running a server


## ruby
## terminal
## chrome

- enable chrome://flags/#show-saved-copy for offline versions of all your pages
- ⌘-⌥-i will toggle the dev tools
- ⌘-⌥-j will open and toggle the console in devtools
- ⌘-K will clear the input
- ⌘-⇧-D will toggle the view of the devtools dock

## mac

### Spotlight

- Open Spotlight Search bar with ⌘-Space
- open a file in Finder from Spotlight results with ⌘-Enter

## markdown

#### Linking to another point within a document

Linking to a certain anchor point within a document is easy as long as it gets directed to a header.

All you gots to do is is make a regular link with a reference to the header name like this: `[words to display](#header-name)`

Let's go to the Bash shortcuts yaaaay! [BASH YO FACE](#bash).

#### Github Flavored Checklists

- [ ] Write out instructions for checklist with `- [ ] item`
- [x] complete an item by putting an x in the box
- [ ] add as many items to the list as necessary

## NPM

### Yarn

Instead of `npm install` which downloads dependencies for every new project, use [Yarn](https://yarnpkg.com/en/) which caches your dependencies locally and takes a fraction of the time.
