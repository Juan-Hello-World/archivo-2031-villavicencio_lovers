| Hallazgo | Dónde estaba | Técnica de Git | Comando exacto | Referencia |
|---|---|---|---|---|
| FRAG-01 | bitacora archivada en la rama principal | commit anterior al que lo borró | `git show 125914e90b9d95bb700454f336715ee5cb1b2f4c^:bitacora/frag-01.txt > bitacora/frag-01.txt` | `125914e90b9d95bb700454f336715ee5cb1b2f4c` |
| FRAG-02 | respaldo previo al incidente | lectura del mensaje de una etiqueta | `git show c96c9af06b4f94c9209d7e716655eddf0835bcc2` | `c96c9af06b4f94c9209d7e716655eddf0835bcc2` |
| GLIFO | respaldo previo al incidente | extraer archivo de una etiqueta | `git show c96c9af06b4f94c9209d7e716655eddf0835bcc2:assets/sello.svg > assets/sello.svg` | `c96c9af06b4f94c9209d7e716655eddf0835bcc2` |