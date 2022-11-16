# vim
Personal vim cheat sheet

## Commands to internalize

- `b`: move backwards word by word
- `e`: jump to the end of a word
- `ge`: jump to the end of the previous word
<hr />

- `f{character}`: move to the next occurence of a character in a line
- `F{character}`: move to the previous occurence of a character in a line
- `t{character}`: move just before `f{character}` (think of as "un[t]il")
- `T{character}`: move just after `F{character}`
- `;`: repeat the last character search forwards
- `,`: repeat the last character search backwards
<hr />

- `}`: jump entire paragraph downwards
- `{`: jump entire paragraph upwards
- `CTRL-D`: move down half a page
- `CTRL-U`: move up half a page
<hr />

- `*`: search for the word under the cursor forwards
- `#`: search for the word under the cursor backwards
<hr />

- `gd`: jump to the definition of the word under your cursor
- `gf`: jump to the file of the import under your cursor
<hr />

- `{line}gg`: go to a specific line
- `%`: jump to matching `({[]})`
