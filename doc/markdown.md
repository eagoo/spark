[TOC]: #
# Table of Contents
- [Split Layout Control](#split-layout-control)
- [Live Templates](#live-templates)
- [As You Type Enhancements](#as-you-type-enhancements)
    - [Wrap on Typing](#wrap-on-typing)
    - [Auto-format table](#auto-format-table)
    - [Bold, Italic, Strikethrough](#bold-italic-strikethrough)
    - [Copy/Paste](#copypaste)
    - [Table Of Contents](#table-of-contents)


* * *

## Split Layout Control

![Screen Shot Toolbar](img/ScreenShot_toolbar_layout.png)

| Button                                                                            | Action                                 | Notes                                               |
|:----------------------------------------------------------------------------------|:---------------------------------------|:----------------------------------------------------|
| ![Editor Preview](./resources/icons/layout/Editor_preview%402x.png)   | Show editor and preview                |                                                     |
| ![Preview Only](./resources/icons/layout/Preview_only%402x.png)       | Show preview only                      |                                                     |
| ![Editor only](./resources/icons/layout/Editor_only%402x.png)         | Show editor only                       |                                                     |
| ![Html Preview](./resources/icons/layout/Html_preview%402x.png)       | Show HTML preview                      |                                                     |
| ![Html Modified](./resources/icons/layout/Html_modified%402x.png)     | Show HTML text used for browser        |                                                     |
| ![Html Unmodified](./resources/icons/layout/Html_unmodified%402x.png) | Show plain HTML as generated by parser | Plain HTML as converted from markdown by the parser |

Actions available but not in the toolbar. Can be mapped to shortcuts.

| Non Toolbar Actions                                                                           | Action                | Notes                                                             |
|:----------------------------------------------------------------------------------------------|:----------------------|:------------------------------------------------------------------|
| ![Cycle Editor Preview](./resources/icons/layout/Cycle_editor_preview%402x.png)   | Cycle split layout    |                                                                   |
| ![Toggle Editor Preview](./resources/icons/layout/Toggle_editor_preview%402x.png) | Toggle Editor Layout  | toggles preview on/off                                            |
| ![Cycle Html](./resources/icons/layout/Cycle_html%402x.png)                       | Cycle preview content | cycle through preview, modified and unmodified HTML preview types |

![Screen Shot Toolbar](img/ScreenShot_toolbar.png)

| Button                                                                                                               | Action                     | Notes                                                                                                                          |
|:---------------------------------------------------------------------------------------------------------------------|:---------------------------|:-------------------------------------------------------------------------------------------------------------------------------|
| ![Editor Actions Wrap On Typing](./resources/icons/editor_actions/Wrap_on_typing%402x.png)               | Toggle wrap on typing      |                                                                                                                                |
| ![Editor Actions Bold](./resources/icons/editor_actions/Bold%402x.png)                                   | Toggle bold text           |                                                                                                                                |
| ![Editor Actions Italic](./resources/icons/editor_actions/Italic%402x.png)                               | Toggle italic text         |                                                                                                                                |
| ![Editor Actions Strikethrough](./resources/icons/editor_actions/Strike_through%402x.png)                | Toggle strike through text |                                                                                                                                |
| ![Editor Actions Code Span](./resources/icons/editor_actions/Code_span%402x.png)                         | Toggle code span           |                                                                                                                                |
| ![Icons Editor Actions Link](./resources/icons/editor_actions/Link%402x.png)                             | Insert explicit link       |                                                                                                                                |
| ![Editor Actions Quote Remove](./resources/icons/editor_actions/Quote_remove%402x.png)                   | Decrease quote level       |                                                                                                                                |
| ![Editor Actions Quote Add](./resources/icons/editor_actions/Quote_add%402x.png)                         | Increase quote level       |                                                                                                                                |
| ![Editor Actions Header Level Up](./resources/icons/editor_actions/Header_level_up%402x.png)             | Increase header level      |                                                                                                                                |
| ![Editor Actions Header Level Down](./resources/icons/editor_actions/Header_level_down%402x.png)         | Decrease header level      |                                                                                                                                |
| ![Editor Actions Header Toggle Type](./resources/icons/editor_actions/Header_toggle_type%402x.png)       | Toggle header type         |                                                                                                                                |
| ![Editor Actions List Unindent](./resources/icons/editor_actions/List_unindent%402x.png)                 | Un-Indent list item        |                                                                                                                                |
| ![Editor Actions List Indent](./resources/icons/editor_actions/List_indent%402x.png)                     | Indent list item           |                                                                                                                                |
| ![Editor Actions List Tight](./resources/icons/editor_actions/List_tight%402x.png)                       | Single space list          | Single space all items in a list. Caret placed on one of the list items                                                        |
| ![Editor Actions List Loose](./resources/icons/editor_actions/List_loose%402x.png)                       | Double space list          | Double space all items in a list. Caret placed on one of the list items                                                        |
| ![Editor Actions List Bullet Items](./resources/icons/editor_actions/List_bullet_items%402x.png)         | Bullet list                | Convert caret item or items in selection  to bullet list items. If all are already bullet items then convert to plain text     |
| ![Editor Actions List Ordered Items](./resources/icons/editor_actions/List_ordered_items%402x.png)       | Numbered list              | Convert caret item or items in selection  to numbered list items. If all are already numbered items then convert to plain text |
| ![Editor Actions List Task Items](./resources/icons/editor_actions/List_task_items%402x.png)             | Task list                  | Convert caret item or items in selection  to task list items. If all are already task items then convert to plain text         |
| ![Editor Actions List Toggle Item Done](./resources/icons/editor_actions/List_toggle_item_done%402x.png) | Toggle task item done      | Toggle done status of caret item or items in selection                                                                         |
| ![Auto Format Table](./resources/icons/editor_actions/AutoFormat_table%402x.png)                         | Toggle auto-format table   | Toggle format table as you type mode.                                                                                          |
| ![Editor Actions Insert Table](./resources/icons/editor_actions/Insert_table%402x.png)                   | Insert table               | Inserts a 1x3 table that you can edit to add more rows and columns.                                                            |
| ![Editor Actions Insert Table Row](./resources/icons/editor_actions/Insert_table_row%402x.png)           | Insert table row           | Insert a row below the caret. Also done by <kbd>ENTER</kbd>                                                                    |
| ![Editor Actions Insert Table Column](./resources/icons/editor_actions/Insert_table_column%402x.png)     | Insert table column        | Insert a column left of the column with caret.                                                                                 |
| ![Delete Table Row](./resources/icons/editor_actions/Delete_table_row%402x.png)                          | Delete table row           | Delete the row with the caret. Also done by <kbd>ENTER</kbd>                                                                   |
| ![Delete Table Column](./resources/icons/editor_actions/Delete_table_column%402x.png)                    | Delete table column        | Delete the column with the column with caret.                                                                                  |
| ![Editor Actions Reformat Element]                                                                                   | Reformat current element   | Wrap paragraph, format table or update table of contents element                                                               |
| ![Editor Actions Reformat Document]                                                                                  | Reformat current document  | Apply code style to current document                                                                                           |
| ![Editor Actions Copy Jira](./resources/icons/editor_actions/Copy_jira%402x.png)                         | Copy JIRA formatted text   | Copy current selection or document as JIRA formatted text                                                                      |
| ![Editor Actions Export Html](./resources/icons/editor_actions/Export_html%402x.png)                     | Export Rendered Html       | Export rendered HTML as per rendering profile                                                                                  |

## Live Templates

| Element           | Abbreviation    | Expansion                                               |
|:------------------|:----------------|:--------------------------------------------------------|
| Abbreviation      | `.abbreviation` | `*[]: `                                                 |
| Code fence        | `.codefence`    | \`\`\` ... \`\`\`                                       |
| Emoji             | `.emoji`        | `::`                                                    |
| Explicit link     | `.link`         | `[]()`                                                  |
| Footnote          | `.footnote`     | `[^]: `                                                 |
| Footnote Ref      | `.rfootnote`    | `[^]`                                                   |
| Image             | `.image`        | `![]()`                                                 |
| Ref image         | `.rimage`       | `![][]`                                                 |
| Ref link          | `.rlink`        | `[][]`                                                  |
| Reference         | `.reference`    | `[]: `                                                  |
| Table             | `.table`        | <pre><code>`|   |`&#10;`|---|`&#10;`|   |`</code></pre> |
| Task              | `.task`         | `- [ ] `                                                |
| Table of Contents | `.toc`          | `[TOC]: #`                                              |
| Wiki link         | `.wikilink`     | `[[]]`                                                  |

## As You Type Enhancements

### Wrap on Typing

With `Wrap on typing` option enabled, typing in a text block will
re-format the text block when a space is typed and the line containing
the caret extends beyond the current right margin. The limitation on
when wrapping is done is intended to reduce the overhead and delay when
typing.

<kbd><kbd>BACKSPACE</kbd></kbd> will reformat the paragraph every time.

Additionally, typing/backspacing a space or a block quote `>` before the
first character of a paragraph will optionally match the block quote
markers and indentation on all the continuation lines for the paragraph.

Similarly, typing between a list marker and the first character of the
paragraph will optionally indent the continuation lines to line them up
with the first position of the text on the first line.

![Text Wrap](./assets/images/TextWrap.gif)

### Auto-format table

With `Auto-format table on typing` enabled will result in the table
formatting options being applied as you edit the table. This does delay
the typing but does make it easier to see the results. When performing
extensive edits to a table you can temporarily turn off this options on
the toolbar.

![Table Auto Format](./assets/images/TableAutoFormat.gif)

If `Add missing columns` is enabled the typing before the leftmost pipe
character will insert a column into the table before the first column.
Typing after the rightmost pipe character will add a column after the
last. If the table rows have un-even column numbers then reformatting a
table via the `Format element` button will also add columns but will do
so at a location based on the column that contains the caret. This way
you can control where the missing columns are inserted. For full control
you should use the `Insert table column` button.

Delete empty row/col on backspace will automatically delete a row or
column when <kbd>BACKSPACE</kbd> is performed in an empty row/column.
Row deletion has priority over column deletion.

Insert on <kbd>ENTER</kbd> will add an empty table row below the row
that contains the caret.

![Table Add Missing](./assets/images/TableAddMissing.gif)

### Bold, Italic, Strikethrough

Automatic closing of bold, italic and strikethrough markers can be
turned on in <kbd>Editor > Code Style > Markdown</kbd>. Enabling each
option will add a closing character. If however you type a space after
the initial character then the added closing one will be removed.

![Assets Smart Edit](./assets/images/SmartEdit.gif)

### Copy/Paste

When pasting markdown text copied from a markdown file link and footnote
references will automatically paste the references at the end of the
file so that these references resolve in the destination file.

Links and link references will also be adjusted to reflect the change in
the source reference file. The destination link address format will be
changed to absolute URL format if the destination file link cannot be
resolved in the original link format.

### Table Of Contents

Table of contents for your document can be generated for standard
markdown parsers that do not support a table of contents element.

The lines after the `[TOC]: #` tag are updated to reflect the content of
the document when you reformat document
![Editor Actions Reformat Document] or reformat element
![editor actions reformat element]. More details in
[[Adding a Table of Contents]]

For a toc element `[TOC levels=3]: #### "Table of Contents"` and these
headers in the document:

```markdown
# Heading **some bold** 1
## Heading 1.1 _some italic_
### Heading 1.1.1
### Heading 1.1.2  **_some bold italic_**
# Heading 2
### Heading 2.0.1
```

After an update the table of contents element will look like the
following:

**Markdown version:**

```markdown
[TOC levels=1-3]: #### "Contents"

#### Contents
- [Heading **some bold** 1](#heading-some-bold-1)
    - [Heading 1.1 _some italic_](#heading-11-some-italic)
        - [Heading 1.1.1](#heading-111)
        - [Heading 1.1.2  **_some bold italic_**](#heading-112--some-bold-italic)
- [Heading 2](#heading-2)
    - [Heading 2.0.1](#heading-201)
```

#### Contents

- [Heading **some bold** 1](#heading-some-bold-1)
    - [Heading 1.1 _some italic_](#heading-11-some-italic)
        - [Heading 1.1.1](#heading-111)
        - [Heading 1.1.2  **_some bold italic_**](#heading-112--some-bold-italic)
- [Heading 2](#heading-2)
    - [Heading 2.0.1](#heading-201)

* * *

**HTML version:**

```markdown
[TOC levels=1-3]: #### "Contents"

<div><h4>Contents</h4>
  <ul>
    <li><a href="#heading-some-bold-1">Heading <strong>some bold</strong> 1</a>
    <ul>
      <li><a href="#heading-11-some-italic">Heading 1.1 <em>some italic</em></a>
      <ul>
        <li><a href="#heading-111">Heading 1.1.1</a></li>
        <li><a href="#heading-112--some-bold-italic">Heading 1.1.2  <strong><em>some bold italic</em></strong></a>
      </ul></li>
    </ul></li>
    <li><a href="#heading-2">Heading 2</a>
    <ul>
      <li><a href="#heading-201">Heading 2.0.1</a></li>
    </ul></li>
  </ul>
</div>
```

<div><h4>Contents</h4>
  <ul>
    <li><a href="#heading-some-bold-1">Heading <strong>some bold</strong> 1</a>
    <ul>
      <li><a href="#heading-11-some-italic">Heading 1.1 <em>some italic</em></a>
      <ul>
        <li><a href="#heading-111">Heading 1.1.1</a></li>
        <li><a href="#heading-112--some-bold-italic">Heading 1.1.2  <strong><em>some bold italic</em></strong></a>
      </ul></li>
    </ul></li>
    <li><a href="#heading-2">Heading 2</a>
    <ul>
      <li><a href="#heading-201">Heading 2.0.1</a></li>
    </ul></li>
  </ul>
</div>

[Editor Actions Reformat Document]: ./resources/icons/editor_actions/Reformat_document%402x.png
[Editor Actions Reformat Element]: ./resources/icons/editor_actions/Reformat_element%402x.png
