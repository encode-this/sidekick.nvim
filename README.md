# sidekick.nvim
An outline window that's always by your side (except for when it's not).

```
   _____ _     __     __ __ _      __   
  / ___/(_)___/ /__  / //_/(_)____/ /__ 
  \__ \/ / __  / _ \/ ,<  / / ___/ //_/ 
 ___/ / / /_/ /  __/ /| |/ / /__/ ,<    
/____/_/\__,_/\___/_/ |_/_/\___/_/|_|   
=======================================
```

### TODO

- [x] Jump from outline to definition
- [ ] Update outline on editor events
  - [x] Buffer save
  - [ ] Change active window
- [ ] Document highlight groups so that colorschemes can explicitly support them.
- [ ] Add custom fold highlight while we want for neovim bug about highlighting folds to get fixed.
- [ ] Display filename (buffer name) in sidekick.
- [ ] Allow empty sidekick window. Currently we just don't open an outline window if the current bufffer is empty or corresponds to an un-supported (by treesitter) filetype.
- [ ] Set window settings to stop context.vim from popping up.
- [ ] Add documentation.
- [ ] Improve plugin configs
  - [ ] Add supported options to documentation.
  - [ ] Add error-checking / default values.

### Roadmap

- [ ] Use treesitter to generate outline for "standard" queries (`queries/$LANG/locals.scm`)  
- [ ] Sort by order or kind.  
- [ ] Use treesitter to generate outline for custom queries (`queries/$LANG/sidekick.scm`)  
- [ ] Generate outline based on LSP.  
- [ ] Pop-up documentation for symbol when using LSP.  
- [ ] After getting experience, re-write most of codebase using an extensible system to allow end users to populate outline window.
- [ ] Let users specify what definitions get shown for standard queries.   


### Maybe features  

- [ ] Generate outline based on tags file.  
- [ ] When using treesitter for outline *and* LSP is available, pop-up documentation for symbol.
