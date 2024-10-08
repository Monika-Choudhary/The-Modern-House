# The-Modern-House

## HEADER
### Hintergrund und Schriftfarbe:
- **`bg-white`**: Legt den Hintergrund auf weiß fest.
- **`text-black`**: Macht die Schriftfarbe schwarz.

### Struktur des Headers:
- **`flex justify-between items-center`** im Header erstellt ein Layout mit Flexbox, wo:
  - **`justify-between`**: Richtet die Hauptelemente (div, h1, div) mit Platz zwischen ihnen aus.
  - **`items-center`**: Richtet die Elemente vertikal in der Mitte aus.

### Erster div (Kaufen, Verkaufen, Journal):
- **`flex`** innerhalb des `ul`: Organisiert die `li` in einer horizontalen Linie.
- **`space-x-4`**: Fügt einen Abstand von 1rem (16px) zwischen den `li`-Elementen hinzu.
- **`hover:underline cursor-pointer`**: Fügt beim Hover eine Unterstreichung hinzu, um es interaktiv zu machen.

### Titel h1:
- **`text-3xl`**: Macht den Text des `h1` größer.
- **`font-bold`**: Macht den Text fett.

### Zweiter div (Verzeichnis, Shop, Über uns usw.):
- Ähnlich wie der erste div, aber auch mit horizontal ausgerichteten Icons.
- **`items-center`**: Stellt sicher, dass die Icons mit dem Text ausgerichtet sind.

## Anpassungen für die Responsivität:

### Flex-Struktur:
- Es wird `flex-col md:flex-row` verwendet, damit das Layout auf kleinen Bildschirmen vertikal und auf mittleren und großen Bildschirmen horizontal ist.

### Padding:
- Es werden unterschiedliche Padding-Werte für verschiedene Bildschirmgrößen angewendet:
  - `p-6` für kleine Bildschirme.
  - `md:p-8` für mittlere Bildschirme.
  - `lg:p-10` für große Bildschirme.

### Schriftgröße:
- `text-base` wird für die Schriftgröße auf kleinen Bildschirmen verwendet, und `md:text-lg` für mittlere Bildschirme.
- Die `h1` hat `text-2xl` auf kleinen Bildschirmen, `md:text-3xl` auf mittleren Bildschirmen und `lg:text-4xl` auf großen Bildschirmen.

### Unterer Rand:
- `mb-4 md:mb-0` wird dem ersten `div` hinzugefügt, um einen unteren Rand anzuzeigen, wenn es auf kleinen Bildschirmen angezeigt wird, und diesen Rand auf mittleren und großen Bildschirmen zu entfernen.
