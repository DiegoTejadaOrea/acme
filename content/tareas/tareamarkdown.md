## First Header 2 ##

This is a normal paragraph following a header. Knausgaard kale chips snackwave microdosing cronut copper mug swag synth bitters letterpress glossier **craft beer**. Mumblecore bushwick authentic gochujang vegan chambray meditation jean shorts irony. Viral farm-to-table kale chips, pork belly palo santo distillery activated charcoal aesthetic jianbing air plant woke lomo VHS organic. Tattooed locavore succulents heirloom, small batch sriracha echo park DIY af. Shaman you probably haven’t heard of them copper mug, crucifix green juice vape *single-origin coffee* brunch actually. Mustache etsy vexillologist raclette authentic fam. Tousled beard humblebrag asymmetrical. I love turkey, I love my job, I love my friends, I love Chardonnay!

Deae legum paulatimque terra, non vos mutata tacet: dic. Vocant docuique me plumas fila quin afuerunt copia haec o neque.

On big screens, paragraphs and headings should not take up the full container width, but we want tables, code blocks and similar to take the full width.

Scenester tumeric pickled, authentic crucifix post-ironic fam freegan VHS pork belly 8-bit yuccie PBR&B. **I love this life we live in**.

## Second Header 2 ##

>This is a blockquote following a header. Bacon ipsum dolor sit amet t-bone doner shank drumstick, pork belly porchetta chuck sausage brisket ham hock rump pig. Chuck kielbasa leberkas, pork bresaola ham hock filet mignon cow shoulder short ribs biltong.

## Header 3 
```
This is a code block following a header.
```
Next level leggings before they sold out, PBR&B church-key shaman echo park. Kale chips occupy godard whatever pop-up freegan pork belly selfies. Gastropub Belinda subway tile woke post-ironic seitan. Shabby chic man bun semiotics vape, chia messenger bag plaid cardigan.

#### Header 4

- This is an unordered list following a header.
- This is an unordered list following a header.
- This is an unordered list following a header.

##### Header 5
1. This is an ordered list following a header.
2. This is an ordered list following a header.
3. This is an ordered list following a header.

###### Header 6
| What	  | Follows  |
| --------|----------|
| A table |	A header |
| A table |	A header |
| A table |	A header |

---

There’s a horizontal rule above and below this.

---

Here is an unordered list:

- Liverpool F.C.
- Chelsea F.C.
- Manchester United F.C.

And an ordered list:

1. Michael Brecker
2. Seamus Blake
3. Branford Marsalis

And an unordered task list:

 - [x] Create a Hugo theme
 - [x] Add task lists to it
 - [ ] Take a vacation

 And a “mixed” task list:

- [ ] Pack bags
- ?
- [ ] Travel!

And a nested list:

- Jackson 5
  - Michael
  - Tito
  - Jackie
  - Marlon
  - Jermaine
- TMNT
  - Leonardo
  - Michelangelo
  - Donatello
  - Raphael

Definition lists can be used with Markdown syntax. Definition headers are bold.

**Name**

Godzilla

**Born**

1952

**Birthplace**

Japan

**Color**

Green

---

Tables should have bold headings and alternating shaded rows.

-------------------------------------------
| **Artist**      | **Album**      | **Year** |
| ----------------|----------------|------|
| Michael Jackson |	Thriller	     |1982  |
| Prince          |	Purple Rain    |1982  |
| Beastie Boys    |	License to Ill |1982  |

If a table is too wide, it should scroll horizontally.

-------------------------------------------
| **Artist**      | **Album**      | **Year** |
| ----------------|----------------|------|
| Michael Jackson |	Thriller	     |1982  |
| Prince          |	Purple Rain    |1982  |
| Beastie Boys    |	License to Ill |1982  |

Code snippets like ```var foo = "bar";``` can be shown inline.

Also, ```this should vertically align``` ~~with this~~``` and ~~this~~.

---
Code can also be shown in a block element.
```
foo := "bar";
bar := "foo";
```

Code can also use syntax highlighting.
```javascript
func main() {
  input := `var foo = "bar";`

  lexer := lexers.Get("javascript")
  iterator, _ := lexer.Tokenise(nil, input)
  style := styles.Get("github")
  formatter := html.New(html.WithLineNumbers())

  var buff bytes.Buffer
  formatter.Format(&buff, style, iterator)

  fmt.Println(buff.String())
}
```

Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.

```

Small images should be shown at their actual size.

https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/Picea_abies_shoot_with_buds%2C_Sogndal%2C_Norway.jpg/240px-Picea_abies_shoot_with_buds%2C_Sogndal%2C_Norway.jpg