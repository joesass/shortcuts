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
- Delete a whole line with control-shift-k
- Select a whole line with command-l

### open-in-browser package

[This package](https://atom.io/packages/open-in-browser) is essential if you are doing any work on plain HTML, CSS or Javascript files without running a server


## ruby
## terminal
## chrome

- enable chrome://flags/#show-saved-copy for offline versions of all your pages
- Command-Option-i will toggle the dev tools
- Command-K will clear the input

## mac

### Spotlight

- Open Spotlight Search bar with Command-Space
- open a file in Finder from Spotlight results with Command-Enter

## markdown

#### Linking to another point within a document

Linking to a certain anchor point within a document is easy as long as it gets directed to a header.

All you gots to do is is make a regular link with a reference to the header name like this: `[words to display](#header-name)`

Let's go to the Bash shortcuts yaaaay! [BASH YO FACE](#bash).

#### Github Flavored Checklists

- [ ] Write out instructions for checklist with `- [ ] item`
- [x] complete an item by putting an x in the box
- [ ] add as many items to the list as necessary
