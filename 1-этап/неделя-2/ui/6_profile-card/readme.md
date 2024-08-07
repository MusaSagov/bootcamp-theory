### Result

![alt text](<Screenshot from 2024-07-07 21-55-39.png>)

## HTML

1. Создайте `<div>` с классом `profile-container`.
2. Внутри `profile-container` создайте `<div>` с классом `profile-card`.
3. Внутри `profile-card` создайте `<img>` с классом `profile-image` и атрибутами `src укажите путь к файлу avatar.png` и `alt`.
4. Под изображением добавьте заголовок `<h2>` с классом `profile-name`.
5. Под заголовком добавьте абзац `<p>` с классом `profile-description`.
6. Под абзацем добавьте кнопку `<button>` с классом `contact-button`.

## CSS

##### Добавьте стили для `profile-container`:

1. Высота: `100vh`.
2. Цвет фона: `#f0f0f0`.
3. Отображение: `flex`.
4. Выравнивание по горизонтали: `center`.
5. Выравнивание по вертикали: `center`.

##### Добавьте стили для `profile-card`:

1. Отображение: `flex`.
2. Направление flex: `column`.
3. Отступ между элементами: `10px`.
4. Выравнивание по горизонтали: `center`.
5. Фон: `#fff`.
6. Радиус границы: `8px`.
7. Тень: `0 4px 8px rgba(0, 0, 0, 0.1)`.
8. Отступы: `20px`.
9. Максимальная Ширина: `300px`.
10. Ширина: `100%`.
11. Семейство шрифтов: `Consolas, sans-serif`

##### Добавьте стили для `profile-image`:

1. Радиус границы: `50%`.
2. Ширина: `100px`
3. Высота: `100px`.
4. Заполнение объекта: `cover`.

##### Добавьте стили для `profile-name`:

1. Размер шрифта: `1.5em`.

##### Добавьте стили для `profile-description`:

1. Цвет текста: `#777`.

##### Добавьте стили для `.contact-button`:

1. Фон: `#007BFF`.
2. Цвет текста: `#fff`.
3. Радиус границы: `5px`.
4. Отступы: `10px 20px`.
5. Курсор: `pointer`.
6. Переход: `background 0.3s`.

##### Добавьте стили для эффекта при наведении на `.contact-button`:

1. Фон при наведении:` #0056b3`.
