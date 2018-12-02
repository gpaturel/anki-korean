# Korean Conjugation:
- [Wiktionary](https://en.wiktionary.org/wiki/어둡다#Conjugation)
- [Dongsa Korean Verb Conjugator](https://koreanverb.app/?search=어둡다)
- [Irregular Verbs](https://www.morninglands.com/korean-language-bank-category/irregular-verbs)

# Fonts:
- [Free Korean Fonts](http://www.freekoreanfont.com)
- [WAZU JAPAN's Gallery of Korean Unicode Fonts](http://www.wazu.jp/gallery/Fonts_Korean.html)


# Note Types: 한국어

## Fields
- 발음  *(prononciation)*
- 한국어  *(coréen), sort by this field in the browser*
- 프랑스어  *(français)*

## Cards
### Front Template
```
<span class="fr">{{프랑스어}}</span>
```

### Back Template
```
{{FrontSide}}
<hr id=answer>
{{한국어}}
<br>
{{발음}}
```

### Styling
```
.card {
  font-family: "UnDotum";
  font-size: 40px;
  text-align: center;
  color: black;
  background-color: white;
  line-height: 1.1;
}
.fr {
  font-family: "Garamond";
  font-size: 24px;
}
.em {
  font-weight: bold;
  color: blue;
}
.light {
  color: #85929e;
}
.small {
  font-size: 50%;
}
.fr .small {
  font-size: 70%;
}
ul {
  font-size: 70%;
  text-align: left;
  list-style-type: square;
  padding-left: 10px;
}
table {
  width: 100%;
  border-collapse: collapse;
  text-align: left;
  font-size: 75%;
}
table td {
  vertical-align: top;
}
#underlined-header th {
  border-bottom: solid;
  border-width: thin;
  border-color: black;
  vertical-align: top;
}
.활용 /* conjugaison */ {
  margin: 1px;
  padding: 2px;
  border: none;
  color: white;
  text-align: center;
  font-weight: normal;
  font-size: 50%;
}
.활용 .bloc {
  margin: inherit;
  padding: inherit;
  border-left: 3px solid black;
  border-radius: 5px;
}
.활용 .부정사 /* infinitif */ {
  margin: inherit;
  padding: inherit;
  background-color: #626567;
  font-weight: bold;
}
.불규칙 /* irrégulier */ {
  padding: inherit;
  color: #78281f;
}
.활용 .불규칙 /* irrégulier */ {
  margin: inherit;
  padding: inherit;
  color: white;
  background-color: #78281f;
  font-weight: bold;
}
.활용 .현재 /* (indicatif) présent */ {
  margin: inherit;
  padding: inherit;
  background-color: #336699;
}
.활용 .과거 /* (indicatif) passé */ {
  margin: inherit;
  padding: inherit;
  background-color: #2673a6;
}
.활용 .미래 /* (indicatif) futur */ {
  margin: inherit;
  padding: inherit;
  background-color: #1a80b2;
}
.활용 .명령법 /* impératif */ {
  margin: inherit;
  padding: inherit;
  background-color: #ff6600;
}
.활용 .연결 /* mots de liaison (connective forms) */ {
  margin: inherit;
  padding: inherit;
  background-color: #0e6251;
}
.하십시오체 /* registre formel poli */ {
  text-align: right;
}
.해요체 /* registre informel poli */ {
  text-align: center;
}
.해체 /* registre informel non poli */ {
  text-align: left;
}
.높임 /* honorifique */ {
  font-size: 70%;
}
@font-face {
  font-family: "UnDotum";
  src: url('_UnDotum.ttf');
}
@font-face {
  font-family: "Garamond";
  src: url('_Garamond-Regular.ttf');
}
```


# Media
```
sha1=$(git log -1 --pretty="format:%h"); for w in $(git show $sha1 | awk '/sound:/{print $1}' | sed 's/^.*:\(.*.mp3\)./\1/'); do echo $w $(git log --name-only $sha1 | grep "/$w"); done
cp collection.media/* ~/.local/share/Anki2/User\ 1/collection.media/
```
