# Análisis de Accesibilidad — Imagen de Coca-Cola

**Imagen analizada:** Botella de Coca-Cola destapándose con splash de líquido y cubos de hielo, sobre fondo verde/blanco con hielo picado en la base.

---

## 1. Texto alternativo (alt text) descriptivo

La imagen transmite información visual compleja (botella destapándose, tapa saltando, chorro de líquido, cubos de hielo flotando) que debe describirse para personas que usan lectores de pantalla.

**Alt text sugerido:**
```
Botella de Coca-Cola destapándose con un chorro de líquido y cubos de hielo flotando alrededor, sobre fondo verde claro con hielo picado en la base.
```

- Si la imagen es puramente decorativa (no aporta información esencial al contenido), debe marcarse como tal: `alt=""`.
- Evitar textos alternativos genéricos como "imagen de Coca-Cola" o dejar el atributo vacío por defecto.

---

## 2. Contraste y legibilidad del texto superpuesto

Si la imagen se usa como fondo para titulares, precios o llamados a la acción, hay que tener en cuenta que el contraste varía por zona:

- **Zona superior:** clara (verde/blanco).
- **Zona inferior:** oscura y muy texturizada (hielo y líquido).

**Recomendaciones:**
- Cumplir con una relación de contraste mínima de **4.5:1** (WCAG 2.1 AA) entre el texto y el fondo.
- Usar una capa de superposición semitransparente (oscura u clara, según la zona) en lugar de colocar texto directamente sobre áreas de alta variación tonal.
- Verificar el contraste con una herramienta como WebAIM Contrast Checker antes de publicar.

---

## 3. Consideraciones para movimiento/animación

Si esta imagen se convierte en GIF, video o animación (por ejemplo, mostrando el splash en movimiento):

- Ofrecer un **botón de pausa/control de reproducción**.
- Evitar destellos o cambios bruscos de luz que puedan afectar a personas con **epilepsia fotosensible**.
- Respetar la preferencia del sistema `prefers-reduced-motion` en el código web para reducir o eliminar el movimiento automático:

```css
@media (prefers-reduced-motion: reduce) {
  .splash-animation {
    animation: none;
  }
}
```

---

*Documento generado como referencia de accesibilidad (WCAG 2.1 AA).*
