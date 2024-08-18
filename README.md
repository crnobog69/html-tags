# HTML Тагови - Брзи Преглед

Овај README пружа кратак опис употребе следећих HTML тагова:

## 1. `<abbr>`
Користи се за означавање скраћеница или акронима. 
```html
<abbr title="World Health Organization">WHO</abbr>
```

## 2. `<code>`
Користи се за приказивање кода унутар текста.
```html
<p>Ево како се користи `for` петља у JavaScript-у:</p>
<code>for(let i = 0; i < 5; i++) { console.log(i); }</code>
```

## 3. `<kbd>`
Означава унос са тастатуре.
```html
<p>Притисните <kbd>Ctrl</kbd> + <kbd>C</kbd> да бисте копирали текст.</p>
```

## 4. `<datalist>` и `<option>`
Користе се за креирање падајућих листа у пољима за унос текста.
```html
<input list="browsers" name="browser">
<datalist id="browsers">
  <option value="Chrome">
  <option value="Firefox">
  <option value="Safari">
</datalist>
```

## 5. `<dialog>`
Користи се за креирање дијалошких прозора.
```html
<dialog id="myDialog">Ово је дијалог прозор.</dialog>
<button onclick="document.getElementById('myDialog').showModal()">Отвори дијалог</button>
```

## 6. `<time>`
Означава време или датум.
```html
<time datetime="2024-08-18">18. август 2024.</time>
```

## 7. `<ruby>`, `<rt>` и `<rp>`
Користе се за приказивање анотација на тексту, често у азијским језицима.
```html
<ruby>漢字<rt>かんじ</rt></ruby>
```

## 8. `<progress>`
Означава напретка задатка.
```html
<progress value="70" max="100">70%</progress>
```

## 9. `<meter>`
Користи се за приказивање мерних података у опсегу.
```html
<meter value="0.7" min="0" max="1">70%</meter>
```

## 10. `<fieldset>` и `<legend>`
Групишу елементе формулара и додају наслов групи.
```html
<fieldset>
  <legend>Лични подаци</legend>
  <label for="name">Име:</label>
  <input type="text" id="name" name="name">
</fieldset>
```

## Закључак
Ово је кратак преглед основних HTML тагова који се могу користити за различите сврхе у веб развоју. За више информација, можете консултовати званичну документацију.
