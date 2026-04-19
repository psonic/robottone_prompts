# Workflow: Psonico Visualizer

1. **Selezione Audio**: Elenca i file in `/data/media/csound` cercandoli per estensione `.wav` o `.mp3`. Scegline uno casualmente.
2. **Generazione Visual**: Usa `render_moviepy_video` per creare un video psichedelico.
   - Lo script Python deve usare l'audio scelto.
   - Deve generare un bel video psichedelico super dettagliato, manim è vettoriale ma puoi usare mille cose per generare il video, pensaci bene.
   - Usa il feedback, è un bel modo per generare video matematici dettagliati.
   - Fai in modo che il video reagisca all'ampiezza dell'audio o a sue determinate frequenze se possibile, rendi evidente la reazione del video all'audio.
   - Se metti del testo animalo deformandolo in modi strani.
   - La durata del video deve coincidere con quella dell'audio.
3. **Output**: Il video verrà salvato in `/data/media/moviepy/` e inviato automaticamente al canale.
