# About

This is an online store app.

# Instruction

In order to start the project:

1. Clone the remote repository to your development environment

```sh
$ git clone https://github.com/Varenthein/wdp-1811-03.git
```

2. Install depedencies

```sh
$ cd wdp-1811-03
$ npm install
```

# Most important tasks

1. `npm run prewatch` - run this scripts if you're willing to have 

2. `npm run watch` - run this scripts during development:
- this script is watching for changes in .scss files and converts it into .css file. 

# Preview

You can see a preview of the project here - [https://romantic-volhard-ce5aef.netlify.com/#](https://romantic-volhard-ce5aef.netlify.com/#)


# Convention and good practices 

## HTML classes
Generally there is no restriction when choosing class names, but **in some cases we use standarized classes**:
- for sections we use classes like section--brands, section--featured etc. 
- for backgrounds we use separated classes like .bg1, .bg2, bg3.../.cov1, .cov2, .cov3... etc.

## Styles (.scss) files structure
The src/sass folder is to keep all .scss files.
1. /bootstrap - for bootstrap styles - we do not edit files here;
2. /components - for all page components (named like _header.scss) and sections styles (named from section classes like _section--brands.scss)

## Commits description
We use **standard good practices** when giving names to commits. It means:
- descriptions are in English;
- descriptions start with simple verb like "add", "do", "fix";
- we avoid overall descriptions like "add styles" or "fix bugs", we prefer detailed descriptions like "add styles for footer";
- we try to keep descriptions short (no more than 50 letters).