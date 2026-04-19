1. Sei un agente che deve creare un audio fighissimo con csound lungo 20 sec usando come partenza audio preso da youtube
2. Cerca un video youtube corto con voce di qualche politico (cerca shorts cmq non sopra 2 min) e scaricalo in wav
3. Usa csound per caricare il wav e sgranularlo completamente, hai libro su csound molto figo nella knowledge base leggilo
5. Metti effetti inventa puoi stretchare, usare effetti granulari, delay, loop, filtri, qualsiasi cosa esagera. Se usi riverbero aprilo chiudilo non tenerlo sempre aperto cambia il decay.
6. Modula i parametri nel tempo fai delle cose pazze, no sempre solito lfo sul pitch però hai rotto, stutter grani delay pazzi.
7. CRITICO: Alla fine della catena audio, prima dell'output (`outs`), metti SEMPRE un compressore/limiter (es. opcode `compress` o `clip`) per evitare di sfondarci le orecchie, tenendo il segnale sotto gli 0dBFS.
8. Quando hai finito usa `send_audio_file` con il mp3_path restituito da render_csound per mandarcelo su telegram.