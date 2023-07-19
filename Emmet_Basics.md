|*Doc. #*|*Rédacteur*|*Création*|*Mise à jour*|
|:---:|:---:|---:|:---|
|***0017***|*Loïc Drouet*|_Vendredi 07 juillet 2023_|_Mercredi 19 juillet 2023_|


<body>

# Emmet Basics

## 1. Configuration

### 1.1 Site web

*Source : [emmet.io](https://emmet.io)*

### 1.2 Activer la tabulation de Emmet dans VS Code pour générer l'expansion liée à l'abbréviation
	
If you want to use the Tab key for expanding the Emmet abbreviations, add the following setting :

`"emmet.triggerExpansionOnTab": true`</code></pre>

This setting allows using the Tab key for indentation when text is not an Emmet abbreviation.

*Source : [Using Tab for Emmet expansions](https://code.visualstudio.com/docs/editor/emmet#_using-tab-for-emmet-expansions)*


## 2. Abbréviations

### 2.1 Lorem

#### 2.1.1 Lorem (1 paragraphe)

L'abbréviation Emmet `lorem` + <kbd>TAB</kbd> ou <kbd>ENTRÉE</kbd> génére le texte :

``` 
Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rem obcaecati aliquam vel aperiam natus placeat, molestiae expedita laudantium iusto, corrupti, fuga deserunt! Deleniti possimus eveniet distinctio ut rerum ex officiis.
``` 

#### 2.1.2 Lorem10 (10 mots)

L'abbréviation Emmet `lorem10` + <kbd>TAB</kbd> ou <kbd>ENTRÉE</kbd> génére le texte :

``` 
Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptates, quam.
``` 

#### 2.1.3 Lorem100 (100 mots)

L'abbréviation Emmet `lorem100` + <kbd>TAB</kbd> ou <kbd>ENTRÉE</kbd> génére le texte :

``` 
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta atque accusamus quas repellat totam beatae laboriosam numquam qui est, quae vel repellendus eveniet commodi, tempore rem, placeat maiores quasi nobis ex. Animi culpa numquam similique amet nihil rerum suscipit laboriosam ipsum possimus soluta ad rem omnis quam cum accusantium eligendi distinctio inventore temporibus pariatur non, porro dicta placeat! Impedit voluptate necessitatibus quae ipsum possimus dignissimos laborum vitae provident nobis adipisci asperiores quibusdam iste deserunt natus, facere repudiandae officiis illo beatae expedita cumque? Corporis molestiae assumenda itaque officia dolores, eaque inventore iste temporibus sit provident aspernatur repellendus. Ipsum porro sint similique.
```

#### 2.2 Créer n paragraphes <em>lorem</em>

Le code Emmet `p*4>lorem` + <kbd>TAB</kbd> ou <kbd>ENTRÉE</kbd> génére le code HTML :

```html
<p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quod iure illo eius labore distinctio eveniet unde culpa rerum adipisci aliquam voluptatibus, nisi praesentium necessitatibus ex perspiciatis in magnam dignissimos. Commodi?</p>
<p>Doloremque molestiae aut beatae dolor delectus fugiat accusamus illo dignissimos exercitationem debitis blanditiis quod eligendi, praesentium aliquam est fugit dolore et? Obcaecati porro corrupti architecto iste mollitia, nulla quibusdam doloremque?</p>
<p>Esse est reprehenderit obcaecati fuga ratione quae odio sit natus, sequi praesentium nemo eaque perspiciatis at doloremque quaerat, dolor saepe nobis soluta? Repellat ipsam laudantium tenetur voluptatibus est? Earum, error!</p>
<p>Non tenetur nemo quasi sed deleniti iusto voluptas debitis ut sequi dignissimos. Iusto, consectetur! Voluptatum, consequuntur necessitatibus aspernatur quidem sint quod magnam nisi, atque obcaecati eveniet esse, ullam praesentium corrupti.</p>
```

### 2.3 Créer une navigation

Le code Emmet `ul#nav>li.item$*4>a{Item $}	` + <kbd>TAB</kbd> ou <kbd>ENTRÉE</kbd> génére le code HTML :

```html
		<ul id="nav">
			<li class="item1"><a href="">Item 1</a></li>
			<li class="item2"><a href="">Item 2</a></li>
			<li class="item3"><a href="">Item 3</a></li>
			<li class="item4"><a href="">Item 4</a></li>
		</ul>
```

### 2.4 Créer une page avec logo et navigation

Le code Emmet `#page>div.logo+ul#navigation>li*5>a{Item $}` + <kbd>TAB</kbd> ou <kbd>ENTRÉE</kbd> génére le code HTML :

```html
<div id="page">
	<div class="logo"></div>
	<ul id="navigation">
		<li><a href="">Item 1</a></li>
		<li><a href="">Item 2</a></li>
		<li><a href="">Item 3</a></li>
		<li><a href="">Item 4</a></li>
		<li><a href="">Item 5</a></li>
	</ul>
</div>
```