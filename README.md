# Figma Controller

**Figma Controller** - це розширення для Visual Studio Code, яке автоматизує взаємодію з Figma через WebDriver. За допомогою цього розширення ви можете автоматизувати процес входу, вибору елементів та експорту стилів та HTML-коду з Figma.

## Основні можливості

- Автоматичний вхід у Figma з використанням збережених облікових даних.
- Вибір фреймів, блоків або елементів у проекті Figma.
- Експорт CSS-стилів та HTML-коду для вибраних елементів.
- Інтерактивний інтерфейс для вибору дій та елементів.

## Встановлення

1. Завантажте `.vsix` файл з [релізів](https://github.com/TechMaverickLab/figma-controller/releases).
2. Відкрийте VS Code.
3. Перейдіть до `Extensions` (`Ctrl+Shift+X`).
4. Натисніть на три крапки у верхньому правому куті та виберіть `Install from VSIX...`.
5. Виберіть завантажений `.vsix` файл та встановіть розширення.

## Використання

1. Після встановлення, іконка Figma з’явиться у боковому меню VS Code.
2. Натисніть на іконку для запуску WebDriver та автоматичного входу у Figma.
3. Виберіть необхідні елементи у проекті для експорту CSS або HTML.
4. Створені файли `figma-project.css` та `figma-project.html` будуть збережені у вказаній директорії.

## Налаштування

Відредагуйте файл `config.json` у корені проекту, щоб змінити URL проекту, email та пароль:

```json
{
  "figma": {
    "url": "https://www.figma.com/design/ваш-проект",
    "email": "your-email@example.com",
    "password": "your-password"
  },
  "projectDirectory": "/шлях/до/папки"
}
```
