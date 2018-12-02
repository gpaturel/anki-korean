# Korean Conjugation:
- [Wiktionary](https://en.wiktionary.org/wiki/어둡다#Conjugation)
- [Dongsa Korean Verb Conjugator](https://koreanverb.app/?search=어둡다)


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
.small {
  font-size: 50%;
}
.fr .small {
  font-size: 70%;
}
ul {
  text-align: left;
}
table {
  width: 100%;
  border-collapse: collapse;
  text-align: center;
  font-size: 75%;
}
#notes th, #notes td {
  font-weight: normal;
  vertical-align: top;
  padding-left: 5px;
}
#notes th {
  padding-bottom: 2px;
}
#notes td {
  color: white;
  background-color: DimGrey;
  font-size: 60%;
}
#underlined-header {
  text-align: left;
}
#underlined-header th {
  border-bottom: solid;
  border-width: thin;
  border-color: black;
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
