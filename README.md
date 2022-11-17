# vim
Personal vim cheat sheet

## Commands to internalize

### Motions

- `b`: move backwards word by word
- `e`: jump to the end of a word
- `ge`: jump to the end of the previous word
<br />

- `f{character}`: move to the next occurence of a character in a line
- `F{character}`: move to the previous occurence of a character in a line
- `t{character}`: move just before `f{character}` (think of as "un[t]il")
- `T{character}`: move just after `F{character}`
- `;`: repeat the last character search forwards
- `,`: repeat the last character search backwards
<br />

- `}`: jump entire paragraph downwards
- `{`: jump entire paragraph upwards
- `CTRL-D`: move down half a page
- `CTRL-U`: move up half a page
<br />

- `*`: search for the word under the cursor forwards
- `#`: search for the word under the cursor backwards
<br />

- `gd`: jump to the definition of the word under your cursor
- `gf`: jump to the file of the import under your cursor
<br />

- `{line}gg`: go to a specific line
- `%`: jump to matching `({[]})`

### Operators

- `g~`: switch case
- `gu`: make lowercase
- `gU`: make uppercase
- `>`: add indentation
- `<`: remove indentation
- `=`: format code
<br />

- `D`: delete from the cursor to the end of the line
- `C`: change from the cursor to the end of the line
- `Y`: copies an entire line
