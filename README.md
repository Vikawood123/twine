# twine
1. Добавление раздела [[Дальше]]
2. Добавление картинки персонажа <img src = "https://github.com/Vikawood123/twine/blob/main/kandinsky-download-1761047079332.png?raw=true">
```
<img src = "https://github.com/Vikawood123/twine/blob/main/kandinsky-download-1761047079332.png?raw=true">
```
3. добавление фона
```
tw-story {
  background-image: url('https://github.com/Vikawood123/twine/blob/main/kandinsky-download-1761045957214.png?raw=true');
    background-size: cover
}

``` 
4. Добавление подложки для текста
```
<div class="text-box">
   МДКд.12.01. 
</div>
```
```
.text-box {
    background-color: rgba(0, 0, 0, 0.7);
    color: white;
    padding: 10px;
    border-radius: 10px;
    margin-top: 10px;
    position: fixed;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);
    width: 80%;
    max-width: 800px;
    z-index: 100;
}

```
