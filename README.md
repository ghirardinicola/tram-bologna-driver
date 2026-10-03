# Bolo Tram

Visualizzazione 3D interattiva del percorso della linea tranviaria di Bologna, realizzata con Three.js.

## Come usare

Apri `index.html` in un browser moderno (si connette a CDN per Three.js).

### Comandi

| Tasto | Azione |
|-------|--------|
| `W` `A` `S` `D` | Muoversi avanti / sinistra / indietro / destra |
| `Q` `E` | Salire / scendere |
| `SHIFT` | Accelerare |
| Mouse (drag) | Guardarsi intorno |
| Scroll | Regolare velocità di movimento |

## Pubblicare su GitHub

```bash
# 1. Creare il repository su GitHub (manualmente o con gh CLI)
gh repo create ghirardinicola/bolo-tram --public --source=. --remote=origin --push

# Oppure seguire le istruzioni da GitHub UI, poi:
git remote add origin https://github.com/ghirardinicola/bolo-tram.git
git add -A
git commit -m "primo commit"
git push -u origin main
```