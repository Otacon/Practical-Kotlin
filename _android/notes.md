
## Margin e Padding
Come ultimi concetti, introduciamo anche quello di **margin** e **padding**.
Il **margin** serve a definire lo spazio da riservare al di fuori della tua view per distanziare gli elementi.
Il **padding** serve a definire lo spazio da riservare all'interno del contenuto della tua view.

Nel caso della `TextView` e' spesso inutile, ma se pensi, per esempio, ad un `Button` (che vedremo nelle sezioni successive),
a volte vuoi avere uno spazio tra il bottone ed un altro elemento, ma anche dello spazio tra il bordo del bottone e il testo.

![Layout intellisense]({{ site.url }}{{ site.baseurl }}/media/1.4/layout_intellisense.png){: .align-center}

Come puoi vedere dall'immagine, il bottone A non ha ne padding ne margin. Il bottone B ha solo padding, mentre il bottone C
ha sia padding che margin.

Su android per definire questi spazi puoi usare una serie di attributi.
Margin:
- `layout_margin` - in tutte le direzioni: `top`, `bottom`, `start` ed `end`;
- `layout_marginHorizontal` - solo `start` e `end`;
- `layout_marginVertical` - solo `top` e `bottom`;
- `layout_marginTop` - solo `top`;
- `layout_marginBottom` - solo `top`;
- `layout_marginStart` - solo `start`;
- `layout_marginEnd` - solo `end`;

Padding:
- `padding` - in tutte le direzioni: `top`, `bottom`, `start` ed `end`;
- `paddingHorizontal` - solo `start` e `end`;
- `paddingVertical` - solo `top` e `bottom`;
- `paddingTop` - solo `top`;
- `paddingBottom` - solo `top`;
- `paddingStart` - solo `start`;
- `paddingEnd` - solo `end`;