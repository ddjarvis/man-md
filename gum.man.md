# [title:GUM manpage]
A tool for glamorous shell scripts.

## NAME
gum - A tool for glamorous shell scripts.

## DESCRIPTION
gum (Charm) is a CLI utility for adding interactive prompts, selectors, and styled UI elements into shell scripts. It acts as a lightweight wrapper for building functional terminal interfaces directly within automated workflows.

## USAGE
`gum [options...] [argument...]`

## OPTIONS
##### `-h, --helpl`
* **Type:** `boolean`
* **Description:** Show context-sensitive help.

##### `-v, --version`
* **Type:** `boolean`
* **Description:** Print the version number

## COMMANDS
### choose
Choose an option from a list of choices

**Usage:** `choose [<options> ...] [flags]`

#### OPTIONS
##### `--cursor-prefix`
* **Default:** `"o "`
* **Description:** Prefix to show on the cursor item (hidden if limit is 1)

##### `--cursor.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--cursor.background`
* **Default:** `""`
* **Description:** Background Color

##### `--cursor.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--cursor.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--cursor.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--cursor.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--cursor.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--cursor.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--cursor.height`
* **Default:** `0`
* **Description:** Text height

##### `--cursor.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--cursor.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--cursor.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--cursor.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--cursor.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--cursor.width`
* **Default:** `0`
* **Description:** Text width

##### `--cursor`
* **Default:** `"> "`
* **Description:** Prefix to show on item that corresponds to the cursor position

##### `--header.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--header.background`
* **Default:** `""`
* **Description:** Background Color

##### `--header.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--header.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--header.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--header.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--header.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--header.foreground`
* **Default:** `"99"`
* **Description:** Foreground Color

##### `--header.height`
* **Default:** `0`
* **Description:** Text height

##### `--header.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--header.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--header.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--header.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--header.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--header.width`
* **Default:** `0`
* **Description:** Text width

##### `--header`
* **Default:** `"Choose:"`
* **Description:** Header value

##### `--height`
* **Default:** `10`
* **Description:** Height of the list

##### `--input-delimiter`
* **Default:** `"\n"`
* **Description:** Option delimiter when reading from STDIN

##### `--item.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--item.background`
* **Default:** `""`
* **Description:** Background Color

##### `--item.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--item.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--item.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--item.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--item.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--item.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--item.height`
* **Default:** `0`
* **Description:** Text height

##### `--item.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--item.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--item.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--item.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--item.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--item.width`
* **Default:** `0`
* **Description:** Text width

##### `--label-delimiter`
* **Default:** `""`
* **Description:** Allows to set a delimiter, so options can be set as label:value

##### `--limit`
* **Default:** `1`
* **Description:** Maximum number of options to pick

##### `--no-limit`
* **Type:** `boolean`
* **Description:** Pick unlimited number of options (ignores limit)

##### `--ordered`
* **Type:** `boolean`
* **Description:** Maintain the order of the selected options

##### `--output-delimiter`
* **Default:** `"\n"`
* **Description:** Option delimiter when writing to STDOUT

##### `--padding`
* **Default:** `"0 0"`
* **Description:** Padding

##### `--select-if-one`
* **Type:** `boolean`
* **Description:** Select the given option if there is only one

##### `--selected-prefix`
* **Default:** `"\/ "`
* **Description:** Prefix to show on selected items (hidden if limit is 1)

##### `--selected.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--selected.background`
* **Default:** `""`
* **Description:** Background Color

##### `--selected.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--selected.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--selected.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--selected.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--selected.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--selected.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--selected.height`
* **Default:** `0`
* **Description:** Text height

##### `--selected.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--selected.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--selected.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--selected.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--selected.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--selected.width`
* **Default:** `0`
* **Description:** Text width

##### `--selected`
* **Default:** `, ...`
* **Description:** Options that should start as selected (selects all if given *)

##### `--show-help`
* **Type:** `boolean`
* **Description:** Show help keybinds

##### `--strip-ansi`
* **Type:** `boolean`
* **Description:** Strip ANSI sequences when reading from STDIN

##### `--timeout`
* **Default:** `0s`
* **Description:** Timeout until choose returns selected element

##### `--unselected-prefix`
* **Default:** `"o "`
* **Description:** Prefix to show on unselected items (hidden if limit is 1)

### confirm
Ask a user to confirm an action

**Usage:** `confirm [<prompt>] [flags]`

#### OPTIONS
##### `--affirmative`
* **Default:** `"Yes"`
* **Description:** The title of the affirmative action

##### `--default`
* **Type:** `boolean`
* **Description:** Default confirmation action

##### `--negative`
* **Default:** `"No"`
* **Description:** The title of the negative action

##### `--padding`
* **Default:** `"0 0"`
* **Description:** Padding

##### `--prompt.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--prompt.background`
* **Default:** `""`
* **Description:** Background Color

##### `--prompt.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--prompt.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--prompt.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--prompt.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--prompt.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--prompt.foreground`
* **Default:** `"#7571F9"`
* **Description:** Foreground Color

##### `--prompt.height`
* **Default:** `0`
* **Description:** Text height

##### `--prompt.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--prompt.margin`
* **Default:** `"0 0 0 1"`
* **Description:** Text margin

##### `--prompt.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--prompt.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--prompt.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--prompt.width`
* **Default:** `0`
* **Description:** Text width

##### `--selected.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--selected.background`
* **Default:** `"212"`
* **Description:** Background Color

##### `--selected.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--selected.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--selected.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--selected.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--selected.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--selected.foreground`
* **Default:** `"230"`
* **Description:** Foreground Color

##### `--selected.height`
* **Default:** `0`
* **Description:** Text height

##### `--selected.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--selected.margin`
* **Default:** `"0 1"`
* **Description:** Text margin

##### `--selected.padding`
* **Default:** `"0 3"`
* **Description:** Text padding

##### `--selected.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--selected.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--selected.width`
* **Default:** `0`
* **Description:** Text width

##### `--show-help`
* **Type:** `boolean`
* **Description:** Show help key binds

##### `--show-output`
* **Type:** `boolean`
* **Description:** Print prompt and chosen action to output

##### `--timeout`
* **Default:** `0s`
* **Description:** Timeout until confirm returns selected value or default if provided

##### `--unselected.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--unselected.background`
* **Default:** `"235"`
* **Description:** Background Color

##### `--unselected.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--unselected.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--unselected.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--unselected.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--unselected.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--unselected.foreground`
* **Default:** `"254"`
* **Description:** Foreground Color

##### `--unselected.height`
* **Default:** `0`
* **Description:** Text height

##### `--unselected.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--unselected.margin`
* **Default:** `"0 1"`
* **Description:** Text margin

##### `--unselected.padding`
* **Default:** `"0 3"`
* **Description:** Text padding

##### `--unselected.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--unselected.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--unselected.width`
* **Default:** `0`
* **Description:** Text width

### file
Pick a file from a folder

**Usage:** `file [<path>] [flags]`

#### OPTIONS
##### `-a, --all`
* **Type:** `boolean`
* **Description:** Show hidden and 'dot' files

##### `--cursor.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--cursor.background`
* **Default:** `""`
* **Description:** Background Color

##### `--cursor.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--cursor.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--cursor.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--cursor.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--cursor.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--cursor.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--cursor.height`
* **Default:** `0`
* **Description:** Text height

##### `--cursor.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--cursor.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--cursor.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--cursor.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--cursor.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--cursor.width`
* **Default:** `0`
* **Description:** Text width

##### `-c, --cursor`
* **Default:** `">"`
* **Description:** The cursor character

##### `--directory`
* **Type:** `boolean`
* **Description:** Allow directories selection

##### `--directory.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--directory.background`
* **Default:** `""`
* **Description:** Background Color

##### `--directory.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--directory.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--directory.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--directory.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--directory.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--directory.foreground`
* **Default:** `"99"`
* **Description:** Foreground Color

##### `--directory.height`
* **Default:** `0`
* **Description:** Text height

##### `--directory.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--directory.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--directory.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--directory.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--directory.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--directory.width`
* **Default:** `0`
* **Description:** Text width

##### `--file`
* **Type:** `boolean`
* **Description:** Allow files selection

##### `--file-size.align`
* **Default:** `"right"`
* **Description:** Text Alignment

##### `--file-size.background`
* **Default:** `""`
* **Description:** Background Color

##### `--file-size.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--file-size.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--file-size.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--file-size.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--file-size.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--file-size.foreground`
* **Default:** `"240"`
* **Description:** Foreground Color

##### `--file-size.height`
* **Default:** `0`
* **Description:** Text height

##### `--file-size.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--file-size.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--file-size.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--file-size.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--file-size.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--file-size.width`
* **Default:** `8`
* **Description:** Text width

##### `--file.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--file.background`
* **Default:** `""`
* **Description:** Background Color

##### `--file.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--file.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--file.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--file.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--file.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--file.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--file.height`
* **Default:** `0`
* **Description:** Text height

##### `--file.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--file.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--file.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--file.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--file.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--file.width`
* **Default:** `0`
* **Description:** Text width

##### `--header.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--header.background`
* **Default:** `""`
* **Description:** Background Color

##### `--header.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--header.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--header.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--header.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--header.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--header.foreground`
* **Default:** `"99"`
* **Description:** Foreground Color

##### `--header.height`
* **Default:** `0`
* **Description:** Text height

##### `--header.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--header.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--header.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--header.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--header.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--header.width`
* **Default:** `0`
* **Description:** Text width

##### `--header`
* **Default:** `""`
* **Description:** Header value

##### `--height`
* **Default:** `10`
* **Description:** Maximum number of files to display

##### `--padding`
* **Default:** `"0 0"`
* **Description:** Padding

##### `-p, --permissions`
* **Type:** `boolean`
* **Description:** Show file permissions

##### `--permissions.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--permissions.background`
* **Default:** `""`
* **Description:** Background Color

##### `--permissions.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--permissions.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--permissions.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--permissions.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--permissions.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--permissions.foreground`
* **Default:** `"244"`
* **Description:** Foreground Color

##### `--permissions.height`
* **Default:** `0`
* **Description:** Text height

##### `--permissions.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--permissions.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--permissions.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--permissions.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--permissions.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--permissions.width`
* **Default:** `0`
* **Description:** Text width

##### `--selected.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--selected.background`
* **Default:** `""`
* **Description:** Background Color

##### `--selected.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--selected.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--selected.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--selected.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--selected.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--selected.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--selected.height`
* **Default:** `0`
* **Description:** Text height

##### `--selected.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--selected.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--selected.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--selected.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--selected.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--selected.width`
* **Default:** `0`
* **Description:** Text width

##### `--show-help`
* **Type:** `boolean`
* **Description:** Show help key binds

##### `-s, --size`
* **Type:** `boolean`
* **Description:** Show file size

##### `--symlink.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--symlink.background`
* **Default:** `""`
* **Description:** Background Color

##### `--symlink.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--symlink.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--symlink.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--symlink.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--symlink.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--symlink.foreground`
* **Default:** `"36"`
* **Description:** Foreground Color

##### `--symlink.height`
* **Default:** `0`
* **Description:** Text height

##### `--symlink.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--symlink.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--symlink.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--symlink.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--symlink.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--symlink.width`
* **Default:** `0`
* **Description:** Text width

##### `--timeout`
* **Default:** `0s`
* **Description:** Timeout until command aborts without a selection

### filter
Filter items from a list

**Usage:** `filter [<options> ...] [flags]`

#### OPTIONS
##### `--cursor-text.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--cursor-text.background`
* **Default:** `""`
* **Description:** Background Color

##### `--cursor-text.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--cursor-text.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--cursor-text.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--cursor-text.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--cursor-text.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--cursor-text.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--cursor-text.height`
* **Default:** `0`
* **Description:** Text height

##### `--cursor-text.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--cursor-text.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--cursor-text.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--cursor-text.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--cursor-text.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--cursor-text.width`
* **Default:** `0`
* **Description:** Text width

##### `--fuzzy`
* **Type:** `boolean`
* **Description:** Enable fuzzy matching; otherwise match from start of word

##### `--fuzzy-sort`
* **Type:** `boolean`
* **Description:** Sort fuzzy results by their scores

##### `--header.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--header.background`
* **Default:** `""`
* **Description:** Background Color

##### `--header.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--header.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--header.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--header.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--header.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--header.foreground`
* **Default:** `"99"`
* **Description:** Foreground Color

##### `--header.height`
* **Default:** `0`
* **Description:** Text height

##### `--header.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--header.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--header.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--header.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--header.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--header.width`
* **Default:** `0`
* **Description:** Text width

##### `--header`
* **Default:** `""`
* **Description:** Header value

##### `--height`
* **Default:** `0`
* **Description:** Input height

##### `--indicator.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--indicator.background`
* **Default:** `""`
* **Description:** Background Color

##### `--indicator.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--indicator.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--indicator.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--indicator.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--indicator.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--indicator.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--indicator.height`
* **Default:** `0`
* **Description:** Text height

##### `--indicator.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--indicator.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--indicator.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--indicator.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--indicator.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--indicator.width`
* **Default:** `0`
* **Description:** Text width

##### `--indicator`
* **Default:** `"o"`
* **Description:** Character for selection

##### `--input-delimiter`
* **Default:** `"\n"`
* **Description:** Option delimiter when reading from STDIN

##### `--limit`
* **Default:** `1`
* **Description:** Maximum number of options to pick

##### `--match.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--match.background`
* **Default:** `""`
* **Description:** Background Color

##### `--match.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--match.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--match.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--match.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--match.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--match.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--match.height`
* **Default:** `0`
* **Description:** Text height

##### `--match.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--match.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--match.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--match.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--match.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--match.width`
* **Default:** `0`
* **Description:** Text width

##### `--no-limit`
* **Type:** `boolean`
* **Description:** Pick unlimited number of options (ignores limit)

##### `--output-delimiter`
* **Default:** `"\n"`
* **Description:** Option delimiter when writing to STDOUT

##### `--padding`
* **Default:** `"0 0"`
* **Description:** Padding

##### `--placeholder.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--placeholder.background`
* **Default:** `""`
* **Description:** Background Color

##### `--placeholder.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--placeholder.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--placeholder.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--placeholder.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--placeholder.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--placeholder.foreground`
* **Default:** `"240"`
* **Description:** Foreground Color

##### `--placeholder.height`
* **Default:** `0`
* **Description:** Text height

##### `--placeholder.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--placeholder.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--placeholder.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--placeholder.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--placeholder.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--placeholder.width`
* **Default:** `0`
* **Description:** Text width

##### `--placeholder`
* **Default:** `"Filter..."`
* **Description:** Placeholder value

##### `--prompt.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--prompt.background`
* **Default:** `""`
* **Description:** Background Color

##### `--prompt.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--prompt.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--prompt.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--prompt.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--prompt.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--prompt.foreground`
* **Default:** `"240"`
* **Description:** Foreground Color

##### `--prompt.height`
* **Default:** `0`
* **Description:** Text height

##### `--prompt.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--prompt.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--prompt.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--prompt.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--prompt.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--prompt.width`
* **Default:** `0`
* **Description:** Text width

##### `--prompt`
* **Default:** `"> "`
* **Description:** Prompt to display

##### `--reverse`
* **Type:** `boolean`
* **Description:** Display from the bottom of the screen

##### `--select-if-one`
* **Type:** `boolean`
* **Description:** Select the given option if there is only one

##### `--selected-indicator.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--selected-indicator.background`
* **Default:** `""`
* **Description:** Background Color

##### `--selected-indicator.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--selected-indicator.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--selected-indicator.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--selected-indicator.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--selected-indicator.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--selected-indicator.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--selected-indicator.height`
* **Default:** `0`
* **Description:** Text height

##### `--selected-indicator.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--selected-indicator.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--selected-indicator.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--selected-indicator.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--selected-indicator.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--selected-indicator.width`
* **Default:** `0`
* **Description:** Text width

##### `--selected-prefix`
* **Default:** `" <?> "`
* **Description:** Character to indicate selected items (hidden if limit is 1)

##### `--selected`
* **Default:** `, ...`
* **Description:** Options that should start as selected (selects all if given *)

##### `--show-help`
* **Type:** `boolean`
* **Description:** Show help keybinds

##### `--sort`
* **Type:** `boolean`
* **Description:** Sort fuzzy results by their scores

##### `--strict`
* **Type:** `boolean`
* **Description:** Only returns if anything matched. Otherwise return Filter

##### `--strip-ansi`
* **Type:** `boolean`
* **Description:** Strip ANSI sequences when reading from STDIN

##### `--text.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--text.background`
* **Default:** `""`
* **Description:** Background Color

##### `--text.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--text.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--text.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--text.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--text.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--text.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--text.height`
* **Default:** `0`
* **Description:** Text height

##### `--text.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--text.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--text.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--text.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--text.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--text.width`
* **Default:** `0`
* **Description:** Text width

##### `--timeout`
* **Default:** `0s`
* **Description:** Timeout until filter command aborts

##### `--unselected-prefix.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--unselected-prefix.background`
* **Default:** `""`
* **Description:** Background Color

##### `--unselected-prefix.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--unselected-prefix.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--unselected-prefix.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--unselected-prefix.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--unselected-prefix.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--unselected-prefix.foreground`
* **Default:** `"240"`
* **Description:** Foreground Color

##### `--unselected-prefix.height`
* **Default:** `0`
* **Description:** Text height

##### `--unselected-prefix.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--unselected-prefix.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--unselected-prefix.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--unselected-prefix.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--unselected-prefix.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--unselected-prefix.width`
* **Default:** `0`
* **Description:** Text width

##### `--unselected-prefix`
* **Default:** `" O "`
* **Description:** Character to indicate unselected items (hidden if limit is 1)

##### `--value`
* **Default:** `""`
* **Description:** Initial filter value

##### `--width`
* **Default:** `0`
* **Description:** Input width

### format
Format a string using a template

**Usage:** `format [<template> ...] [flags]`

#### OPTIONS
##### `-l, --language`
* **Default:** `""`
* **Description:** Programming language to parse code

##### `--strip-ansi`
* **Type:** `boolean`
* **Description:** Strip ANSI sequences when reading from STDIN

##### `--theme`
* **Default:** `"pink"`
* **Description:** Glamour theme to use for markdown formatting

##### `-t, --type`
* **Default:** `"markdown"`
* **Description:** Format to use (markdown,template,code,emoji)

### input
Prompt for some input

**Usage:** `input [flags]`

#### OPTIONS
##### `--char-limit`
* **Default:** `400`
* **Description:** Maximum value length (0 for no limit)

##### `--cursor.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--cursor.background`
* **Default:** `""`
* **Description:** Background Color

##### `--cursor.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--cursor.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--cursor.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--cursor.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--cursor.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--cursor.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--cursor.height`
* **Default:** `0`
* **Description:** Text height

##### `--cursor.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--cursor.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--cursor.mode`
* **Default:** `"blink"`
* **Description:** Cursor mode

##### `--cursor.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--cursor.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--cursor.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--cursor.width`
* **Default:** `0`
* **Description:** Text width

##### `--header.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--header.background`
* **Default:** `""`
* **Description:** Background Color

##### `--header.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--header.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--header.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--header.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--header.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--header.foreground`
* **Default:** `"240"`
* **Description:** Foreground Color

##### `--header.height`
* **Default:** `0`
* **Description:** Text height

##### `--header.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--header.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--header.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--header.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--header.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--header.width`
* **Default:** `0`
* **Description:** Text width

##### `--header`
* **Default:** `""`
* **Description:** Header value

##### `--padding`
* **Default:** `"0 0"`
* **Description:** Padding

##### `--password`
* **Type:** `boolean`
* **Description:** Mask input characters

##### `--placeholder.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--placeholder.background`
* **Default:** `""`
* **Description:** Background Color

##### `--placeholder.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--placeholder.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--placeholder.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--placeholder.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--placeholder.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--placeholder.foreground`
* **Default:** `"240"`
* **Description:** Foreground Color

##### `--placeholder.height`
* **Default:** `0`
* **Description:** Text height

##### `--placeholder.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--placeholder.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--placeholder.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--placeholder.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--placeholder.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--placeholder.width`
* **Default:** `0`
* **Description:** Text width

##### `--placeholder`
* **Default:** `"Type something..."`
* **Description:** Placeholder value

##### `--prompt.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--prompt.background`
* **Default:** `""`
* **Description:** Background Color

##### `--prompt.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--prompt.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--prompt.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--prompt.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--prompt.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--prompt.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--prompt.height`
* **Default:** `0`
* **Description:** Text height

##### `--prompt.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--prompt.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--prompt.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--prompt.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--prompt.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--prompt.width`
* **Default:** `0`
* **Description:** Text width

##### `--prompt`
* **Default:** `"> "`
* **Description:** Prompt to display

##### `--show-help`
* **Type:** `boolean`
* **Description:** Show help keybinds

##### `--strip-ansi`
* **Type:** `boolean`
* **Description:** Strip ANSI sequences when reading from STDIN

##### `--timeout`
* **Default:** `0s`
* **Description:** Timeout until input aborts

##### `--value`
* **Default:** `""`
* **Description:** Initial value (can also be passed via stdin)

##### `--width`
* **Default:** `0`
* **Description:** Input width (0 for terminal width)

### join
Join text vertically or horizontally

**Usage:** `join <text> ... [flags]`

#### OPTIONS
##### `--align`
* **Default:** `"left"`
* **Description:** Text alignment

##### `--horizontal`
* **Type:** `boolean`
* **Description:** Join (potentially multi-line) strings horizontally

##### `--vertical`
* **Type:** `boolean`
* **Description:** Join (potentially multi-line) strings vertically

### log
Log messages to output

**Usage:** `log <text> ... [flags]`

#### OPTIONS
##### `-o, --file`
* **Default:** `STRING`
* **Description:** Log to file

##### `-f, --format`
* **Type:** `boolean`
* **Description:** Format message using printf

##### `--formatter`
* **Default:** `"text"`
* **Description:** The log formatter to use

##### `--key.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--key.background`
* **Default:** `""`
* **Description:** Background Color

##### `--key.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--key.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--key.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--key.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--key.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--key.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--key.height`
* **Default:** `0`
* **Description:** Text height

##### `--key.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--key.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--key.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--key.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--key.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--key.width`
* **Default:** `0`
* **Description:** Text width

##### `--level.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--level.background`
* **Default:** `""`
* **Description:** Background Color

##### `--level.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--level.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--level.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--level.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--level.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--level.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--level.height`
* **Default:** `0`
* **Description:** Text height

##### `--level.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--level.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--level.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--level.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--level.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--level.width`
* **Default:** `0`
* **Description:** Text width

##### `-l, --level`
* **Default:** `"none"`
* **Description:** The log level to use

##### `--message.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--message.background`
* **Default:** `""`
* **Description:** Background Color

##### `--message.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--message.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--message.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--message.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--message.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--message.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--message.height`
* **Default:** `0`
* **Description:** Text height

##### `--message.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--message.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--message.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--message.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--message.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--message.width`
* **Default:** `0`
* **Description:** Text width

##### `--min-level`
* **Default:** `""`
* **Description:** Minimal level to show

##### `--prefix.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--prefix.background`
* **Default:** `""`
* **Description:** Background Color

##### `--prefix.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--prefix.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--prefix.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--prefix.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--prefix.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--prefix.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--prefix.height`
* **Default:** `0`
* **Description:** Text height

##### `--prefix.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--prefix.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--prefix.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--prefix.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--prefix.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--prefix.width`
* **Default:** `0`
* **Description:** Text width

##### `--prefix`
* **Default:** `STRING`
* **Description:** Prefix to print before the message

##### `--separator.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--separator.background`
* **Default:** `""`
* **Description:** Background Color

##### `--separator.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--separator.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--separator.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--separator.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--separator.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--separator.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--separator.height`
* **Default:** `0`
* **Description:** Text height

##### `--separator.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--separator.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--separator.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--separator.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--separator.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--separator.width`
* **Default:** `0`
* **Description:** Text width

##### `-s, --structured`
* **Type:** `boolean`
* **Description:** Use structured logging

##### `--time.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--time.background`
* **Default:** `""`
* **Description:** Background Color

##### `--time.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--time.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--time.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--time.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--time.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--time.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--time.height`
* **Default:** `0`
* **Description:** Text height

##### `--time.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--time.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--time.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--time.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--time.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--time.width`
* **Default:** `0`
* **Description:** Text width

##### `-t, --time`
* **Default:** `""`
* **Description:** The time format to use (kitchen, layout, ansic, rfc822, etc...)

##### `--value.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--value.background`
* **Default:** `""`
* **Description:** Background Color

##### `--value.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--value.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--value.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--value.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--value.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--value.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--value.height`
* **Default:** `0`
* **Description:** Text height

##### `--value.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--value.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--value.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--value.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--value.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--value.width`
* **Default:** `0`
* **Description:** Text width

### pager
Scroll through a file

**Usage:** `pager [<content>] [flags]`

#### OPTIONS
##### `--align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--background`
* **Default:** `""`
* **Description:** Background Color

##### `--bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--border-foreground`
* **Default:** `"212"`
* **Description:** Border Foreground Color

##### `--border`
* **Default:** `"rounded"`
* **Description:** Border Style

##### `--faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--height`
* **Default:** `0`
* **Description:** Text height

##### `--help.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--help.background`
* **Default:** `""`
* **Description:** Background Color

##### `--help.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--help.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--help.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--help.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--help.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--help.foreground`
* **Default:** `"241"`
* **Description:** Foreground Color

##### `--help.height`
* **Default:** `0`
* **Description:** Text height

##### `--help.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--help.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--help.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--help.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--help.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--help.width`
* **Default:** `0`
* **Description:** Text width

##### `--italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--line-number.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--line-number.background`
* **Default:** `""`
* **Description:** Background Color

##### `--line-number.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--line-number.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--line-number.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--line-number.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--line-number.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--line-number.foreground`
* **Default:** `"237"`
* **Description:** Foreground Color

##### `--line-number.height`
* **Default:** `0`
* **Description:** Text height

##### `--line-number.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--line-number.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--line-number.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--line-number.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--line-number.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--line-number.width`
* **Default:** `0`
* **Description:** Text width

##### `--margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--match-highlight.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--match-highlight.background`
* **Default:** `"225"`
* **Description:** Background Color

##### `--match-highlight.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--match-highlight.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--match-highlight.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--match-highlight.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--match-highlight.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--match-highlight.foreground`
* **Default:** `"235"`
* **Description:** Foreground Color

##### `--match-highlight.height`
* **Default:** `0`
* **Description:** Text height

##### `--match-highlight.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--match-highlight.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--match-highlight.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--match-highlight.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--match-highlight.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--match-highlight.width`
* **Default:** `0`
* **Description:** Text width

##### `--match.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--match.background`
* **Default:** `""`
* **Description:** Background Color

##### `--match.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--match.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--match.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--match.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--match.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--match.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--match.height`
* **Default:** `0`
* **Description:** Text height

##### `--match.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--match.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--match.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--match.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--match.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--match.width`
* **Default:** `0`
* **Description:** Text width

##### `--padding`
* **Default:** `"0 1"`
* **Description:** Text padding

##### `--show-line-numbers`
* **Type:** `boolean`
* **Description:** Show line numbers

##### `--soft-wrap`
* **Type:** `boolean`
* **Description:** Soft wrap lines

##### `--strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--timeout`
* **Default:** `0s`
* **Description:** Timeout until command exits

##### `--underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--width`
* **Default:** `0`
* **Description:** Text width

### spin
Display spinner while running a command

**Usage:** `spin <command> ... [flags]`

#### OPTIONS
##### `-a, --align`
* **Default:** `"left"`
* **Description:** Alignment of spinner with regard to the title

##### `--padding`
* **Default:** `"0 0"`
* **Description:** Padding

##### `--show-error`
* **Type:** `boolean`
* **Description:** Show output of command only if the command fails

##### `--show-output`
* **Type:** `boolean`
* **Description:** Show or pipe output of command during execution (shows both STDOUT and STDERR)

##### `--show-stderr`
* **Type:** `boolean`
* **Description:** Show STDERR errput

##### `--show-stdout`
* **Type:** `boolean`
* **Description:** Show STDOUT output

##### `--spinner.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--spinner.background`
* **Default:** `""`
* **Description:** Background Color

##### `--spinner.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--spinner.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--spinner.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--spinner.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--spinner.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--spinner.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--spinner.height`
* **Default:** `0`
* **Description:** Text height

##### `--spinner.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--spinner.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--spinner.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--spinner.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--spinner.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--spinner.width`
* **Default:** `0`
* **Description:** Text width

##### `-s, --spinner`
* **Default:** `"dot"`
* **Description:** Spinner type

##### `--timeout`
* **Default:** `0s`
* **Description:** Timeout until spin command aborts

##### `--title.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--title.background`
* **Default:** `""`
* **Description:** Background Color

##### `--title.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--title.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--title.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--title.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--title.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--title.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--title.height`
* **Default:** `0`
* **Description:** Text height

##### `--title.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--title.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--title.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--title.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--title.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--title.width`
* **Default:** `0`
* **Description:** Text width

##### `--title`
* **Default:** `"Loading..."`
* **Description:** Text to display to user while spinning

### style
Apply coloring, borders, spacing to text

**Usage:** `style [<text> ...] [flags]`

#### OPTIONS
##### `--align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--background`
* **Default:** `""`
* **Description:** Background Color

##### `--bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--height`
* **Default:** `0`
* **Description:** Text height

##### `--italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--strip-ansi`
* **Type:** `boolean`
* **Description:** Strip ANSI sequences when reading from STDIN

##### `--trim`
* **Type:** `boolean`
* **Description:** Trim whitespaces on every input line

##### `--underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--width`
* **Default:** `0`
* **Description:** Text width

### table
Render a table of data

**Usage:** `table [flags]`

#### OPTIONS
##### `--border.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--border.background`
* **Default:** `""`
* **Description:** Background Color

##### `--border.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--border.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--border.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--border.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--border.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--border.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--border.height`
* **Default:** `0`
* **Description:** Text height

##### `--border.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--border.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--border.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--border.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--border.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--border.width`
* **Default:** `0`
* **Description:** Text width

##### `-b, --border`
* **Default:** `"rounded"`
* **Description:** border style

##### `--cell.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--cell.background`
* **Default:** `""`
* **Description:** Background Color

##### `--cell.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--cell.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--cell.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--cell.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--cell.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--cell.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--cell.height`
* **Default:** `0`
* **Description:** Text height

##### `--cell.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--cell.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--cell.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--cell.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--cell.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--cell.width`
* **Default:** `0`
* **Description:** Text width

##### `-c, --columns`
* **Default:** `COLUMNS, ...`
* **Description:** Column names

##### `--fields-per-record`
* **Default:** `0`
* **Description:** Sets the number of expected fields per record

##### `-f, --file`
* **Default:** `""`
* **Description:** file path

##### `--header.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--header.background`
* **Default:** `""`
* **Description:** Background Color

##### `--header.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--header.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--header.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--header.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--header.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--header.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--header.height`
* **Default:** `0`
* **Description:** Text height

##### `--header.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--header.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--header.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--header.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--header.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--header.width`
* **Default:** `0`
* **Description:** Text width

##### `--height`
* **Default:** `0`
* **Description:** Table height

##### `--hide-count`
* **Type:** `boolean`
* **Description:** Hide item count on help keybinds

##### `--lazy-quotes`
* **Type:** `boolean`
* **Description:** If LazyQuotes is true, a quote may appear in an unquoted field and a non-doubled quote may appear in a quoted field

##### `--padding`
* **Default:** `"0 0"`
* **Description:** Padding

##### `-p, --print`
* **Type:** `boolean`
* **Description:** static print

##### `-r, --return-column`
* **Default:** `0`
* **Description:** Which column number should be returned instead of whole row as string. Default=0 returns whole Row

##### `--selected.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--selected.background`
* **Default:** `""`
* **Description:** Background Color

##### `--selected.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--selected.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--selected.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--selected.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--selected.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--selected.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--selected.height`
* **Default:** `0`
* **Description:** Text height

##### `--selected.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--selected.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--selected.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--selected.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--selected.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--selected.width`
* **Default:** `0`
* **Description:** Text width

##### `-s, --separator`
* **Default:** `","`
* **Description:** Row separator

##### `--show-help`
* **Type:** `boolean`
* **Description:** Show help keybinds

##### `--timeout`
* **Default:** `0s`
* **Description:** Timeout until choose returns selected element

##### `-w, --widths`
* **Default:** `WIDTH	S, ...`
* **Description:** Column widths

### version-check
Semver check current gum version

**Usage:** `version-check <constraint> [flags]`

#### }

### write
Prompt for long-form text

**Usage:** `write [flags]`

#### OPTIONS
##### `--base.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--base.background`
* **Default:** `""`
* **Description:** Background Color

##### `--base.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--base.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--base.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--base.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--base.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--base.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--base.height`
* **Default:** `0`
* **Description:** Text height

##### `--base.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--base.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--base.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--base.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--base.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--base.width`
* **Default:** `0`
* **Description:** Text width

##### `--char-limit`
* **Default:** `0`
* **Description:** Maximum value length (0 for no limit)

##### `--cursor-line-number.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--cursor-line-number.background`
* **Default:** `""`
* **Description:** Background Color

##### `--cursor-line-number.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--cursor-line-number.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--cursor-line-number.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--cursor-line-number.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--cursor-line-number.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--cursor-line-number.foreground`
* **Default:** `"7"`
* **Description:** Foreground Color

##### `--cursor-line-number.height`
* **Default:** `0`
* **Description:** Text height

##### `--cursor-line-number.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--cursor-line-number.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--cursor-line-number.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--cursor-line-number.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--cursor-line-number.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--cursor-line-number.width`
* **Default:** `0`
* **Description:** Text width

##### `--cursor-line.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--cursor-line.background`
* **Default:** `""`
* **Description:** Background Color

##### `--cursor-line.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--cursor-line.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--cursor-line.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--cursor-line.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--cursor-line.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--cursor-line.foreground`
* **Default:** `""`
* **Description:** Foreground Color

##### `--cursor-line.height`
* **Default:** `0`
* **Description:** Text height

##### `--cursor-line.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--cursor-line.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--cursor-line.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--cursor-line.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--cursor-line.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--cursor-line.width`
* **Default:** `0`
* **Description:** Text width

##### `--cursor.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--cursor.background`
* **Default:** `""`
* **Description:** Background Color

##### `--cursor.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--cursor.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--cursor.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--cursor.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--cursor.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--cursor.foreground`
* **Default:** `"212"`
* **Description:** Foreground Color

##### `--cursor.height`
* **Default:** `0`
* **Description:** Text height

##### `--cursor.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--cursor.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--cursor.mode`
* **Default:** `"blink"`
* **Description:** Cursor mode

##### `--cursor.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--cursor.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--cursor.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--cursor.width`
* **Default:** `0`
* **Description:** Text width

##### `--end-of-buffer.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--end-of-buffer.background`
* **Default:** `""`
* **Description:** Background Color

##### `--end-of-buffer.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--end-of-buffer.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--end-of-buffer.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--end-of-buffer.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--end-of-buffer.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--end-of-buffer.foreground`
* **Default:** `"0"`
* **Description:** Foreground Color

##### `--end-of-buffer.height`
* **Default:** `0`
* **Description:** Text height

##### `--end-of-buffer.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--end-of-buffer.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--end-of-buffer.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--end-of-buffer.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--end-of-buffer.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--end-of-buffer.width`
* **Default:** `0`
* **Description:** Text width

##### `--header.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--header.background`
* **Default:** `""`
* **Description:** Background Color

##### `--header.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--header.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--header.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--header.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--header.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--header.foreground`
* **Default:** `"240"`
* **Description:** Foreground Color

##### `--header.height`
* **Default:** `0`
* **Description:** Text height

##### `--header.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--header.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--header.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--header.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--header.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--header.width`
* **Default:** `0`
* **Description:** Text width

##### `--header`
* **Default:** `""`
* **Description:** Header value

##### `--height`
* **Default:** `5`
* **Description:** Text area height

##### `--line-number.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--line-number.background`
* **Default:** `""`
* **Description:** Background Color

##### `--line-number.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--line-number.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--line-number.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--line-number.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--line-number.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--line-number.foreground`
* **Default:** `"7"`
* **Description:** Foreground Color

##### `--line-number.height`
* **Default:** `0`
* **Description:** Text height

##### `--line-number.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--line-number.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--line-number.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--line-number.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--line-number.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--line-number.width`
* **Default:** `0`
* **Description:** Text width

##### `--max-lines`
* **Default:** `0`
* **Description:** Maximum number of lines (0 for no limit)

##### `--padding`
* **Default:** `"0 0"`
* **Description:** Padding

##### `--placeholder.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--placeholder.background`
* **Default:** `""`
* **Description:** Background Color

##### `--placeholder.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--placeholder.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--placeholder.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--placeholder.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--placeholder.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--placeholder.foreground`
* **Default:** `"240"`
* **Description:** Foreground Color

##### `--placeholder.height`
* **Default:** `0`
* **Description:** Text height

##### `--placeholder.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--placeholder.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--placeholder.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--placeholder.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--placeholder.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--placeholder.width`
* **Default:** `0`
* **Description:** Text width

##### `--placeholder`
* **Default:** `"Write something..."`
* **Description:** Placeholder value

##### `--prompt.align`
* **Default:** `"left"`
* **Description:** Text Alignment

##### `--prompt.background`
* **Default:** `""`
* **Description:** Background Color

##### `--prompt.bold`
* **Type:** `boolean`
* **Description:** Bold text

##### `--prompt.border-background`
* **Default:** `""`
* **Description:** Border Background Color

##### `--prompt.border-foreground`
* **Default:** `""`
* **Description:** Border Foreground Color

##### `--prompt.border`
* **Default:** `"none"`
* **Description:** Border Style

##### `--prompt.faint`
* **Type:** `boolean`
* **Description:** Faint text

##### `--prompt.foreground`
* **Default:** `"7"`
* **Description:** Foreground Color

##### `--prompt.height`
* **Default:** `0`
* **Description:** Text height

##### `--prompt.italic`
* **Type:** `boolean`
* **Description:** Italicize text

##### `--prompt.margin`
* **Default:** `"0 0"`
* **Description:** Text margin

##### `--prompt.padding`
* **Default:** `"0 0"`
* **Description:** Text padding

##### `--prompt.strikethrough`
* **Type:** `boolean`
* **Description:** Strikethrough text

##### `--prompt.underline`
* **Type:** `boolean`
* **Description:** Underline text

##### `--prompt.width`
* **Default:** `0`
* **Description:** Text width

##### `--prompt`
* **Default:** `"<?> "`
* **Description:** Prompt to display

##### `--show-cursor-line`
* **Type:** `boolean`
* **Description:** Show cursor line

##### `--show-help`
* **Type:** `boolean`
* **Description:** Show help key binds

##### `--show-line-numbers`
* **Type:** `boolean`
* **Description:** Show line numbers

##### `--strip-ansi`
* **Type:** `boolean`
* **Description:** Strip ANSI sequences when reading from STDIN

##### `--timeout`
* **Default:** `0s`
* **Description:** Timeout until choose returns selected element

##### `--value`
* **Default:** `""`
* **Description:** Initial value (can be passed via stdin)

##### `--width`
* **Default:** `0`
* **Description:** Text area width (0 for terminal width)

## COPYRIGHT
(c) 2022-2024 Charmbracelet, Inc.
**Released under MIT license.**
2026-04-16