
# Quelle
- https://www.youtube.com/watch?v=WKIzq6vcO3s

# Ausgangslage
- Alle Beispiele funzen NICHT mit Canary
- Canary funzt AUCH nicht mit Polyfills 

# Vorbereitung für Polyfill 'cqfill'
1. installieren: npm install cqfill 
2. einfügen in 'index.html': <script src="https://unpkg.com/cqfill"></script>
3. einfügen 'fallback' Property für Unterstützung der 'contain' Property. 
   -  '--css-contain: layout style inline-size;'
4. einfügen 'fallback' Regel für Unterstützung der 'container' Query
   - @media --css-container and (min-width: 400px)
5. Starten Live Sever (beliebige Browser)  
6. 'snowpack' funktioniert nicht






