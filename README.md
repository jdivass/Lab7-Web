# 🐍 Snake Game

Juego clásico de Snake construido con **React** y **Babel** via CDN, todo en un solo archivo `index.html`.

## 📁 Archivos

```
/
├── index.html
└── Fruit.png
```

## 🚀 Cómo correrlo

```bash
python3 -m http.server
```

Luego abrir [http://localhost:8000](http://localhost:8000) en el navegador.

## 🎮 Cómo jugar

- Presionar **Start** para comenzar.
- Mover la serpiente con las **flechas del teclado** (`↑ ↓ ← →`).
- Comer la 🍎 fruta otorga **100 puntos** y hace crecer la serpiente.
- La serpiente se **acelera** conforme crece.
- Chocar con una pared o con el propio cuerpo termina el juego.
- Presionar **Try Again** para reiniciar.

## ✅ Cumplimiento de requisitos

### Uso de React — 40 pts

| Requisito | Puntos | Estado |
|-----------|--------|--------|
| Separación en componentes | 20 pts | ✅ |
| Uso de props | 10 pts | ✅ |
| useState y useEffect | 10 pts | ✅ |

### Lógica del juego — 30 pts

| Requisito | Puntos | Estado |
|-----------|--------|--------|
| Movimiento de la serpiente | 10 pts | ✅ |
| Detección de colisiones | 10 pts | ✅ |
| Crecimiento y puntaje | 10 pts | ✅ |

### Estructura del código — 20 pts

| Requisito | Puntos | Estado |
|-----------|--------|--------|
| Código claro y organizado | 10 pts | ✅ |
| Separación de responsabilidades | 10 pts | ✅ |

### Interfaz — 10 pts

| Requisito | Puntos | Estado |
|-----------|--------|--------|
| Presentación visual clara | 10 pts | ✅ |

### Extras — hasta 15 pts

| Extra | Puntos | Estado |
|-------|--------|--------|
| Pantalla de inicio y Game Over | 5 pts | ✅ |
| Aumento de dificultad (a través de la velocidad) | 5 pts | ✅ |
| Animaciones | 5 pts | ❌ |
