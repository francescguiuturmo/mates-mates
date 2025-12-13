# Taules de multiplicar - Practica

Una aplicació web simple per practicar les taules de multiplicar, dissenyada especialment per nens de 3r de primària.

## Característiques

- 🎯 **Practica personalitzada**: Selecciona quines taules vols practicar (1-10)
- ⏱️ **Temps configurable**: Ajusta el temps per pregunta (per defecte 10 segons) i la durada de la partida (per defecte 2 minuts)
- 📊 **Resultats detallats**: Veu els encerts, errors i totes les operacions amb les solucions correctes
- 📱 **Responsiu**: Funciona perfectament en mòbils, tauletes i ordinadors
- 🚀 **Fàcil de desplegar**: Un sol fitxer HTML amb CSS i JavaScript vanilla

## Com utilitzar-ho

1. Configura el temps per pregunta i la durada de la partida
2. Selecciona les taules que vols practicar clicant els botons numèrics (1-10)
3. Prem "Iniciar" per començar la partida
4. Respon cada multiplicació escrivint la resposta i prement Enter o el botó "Comprovar"
5. Al final de la partida veuràs els teus resultats amb totes les operacions

## Desplegament a GitHub Pages

### Opció 1: Pujada directa
1. Puja el fitxer `index.html` a l'arrel del teu repositori de GitHub
2. Ves a Settings → Pages
3. Selecciona "Deploy from a branch"
4. Tria "main" branch i "/ (root)" com a carpeta
5. Prem "Save"
6. La teva aplicació estarà disponible a `https://nomdeltucompte.github.io/nom-del-repositori`

### Opció 2: Amb Git
```bash
# Clona o navega al teu repositori
cd nom-del-repositori

# Afegeix el fitxer
git add index.html
git commit -m "Afegeix aplicació de taules de multiplicar"
git push origin main

# Després activa GitHub Pages des de la configuració del repositori
```

## Tecnologies utilitzades

- **HTML5**: Estructura de l'aplicació
- **CSS3**: Estils moderns i responsiu
- **JavaScript Vanilla**: Lògica del joc sense dependències externes

## Funcionalitats tècniques

- Timers precis amb intervals de 200ms
- Gestió d'estat del joc
- Interfície accessible amb ARIA labels
- CSS optimitzat amb custom properties
- Design responsiu amb media queries
- Input numèric optimitzat per mòbils

## Personalització

Pots modificar fàcilment:
- Colors canviant les variables CSS a `:root`
- Temps per defecte modificant els valors `value` dels inputs
- Rangs de multiplicació ajustant els bucles JavaScript
- Estils visuals editant el CSS

## Llicència

Aquest projecte és de domini públic. Pots utilitzar-lo, modificar-lo i distribuir-lo lliurement.
