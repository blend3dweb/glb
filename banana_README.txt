ФОРМАТ ДАННЫХ ДЛЯ НЕЙРОМОДЕЛИ
==================================================

Структура данных:
- scene_objects: основные объекты сцены (банан, яблоко и т.д.)
- compound_shapes: коллекции bounds, группирующие коллайдеры
- collision_shapes: отдельные коллайдеры (сферы)
- relationships: связи между элементами

Пример использования:
```javascript
// Для Rapier.js
const compound = new RAPIER.ColliderSet();
bounds.colliders.forEach(colliderId => {
  const collider = collision_shapes[colliderId];
  // Создать коллайдер...
});
```
