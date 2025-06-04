il sistemi di coordinate in opengl si aspetta che i vertici degli oggetti di essere normalizzati dopo ogni compilazione del vertex shader

Per normalizzazione si intende che i valori delle coordinate x,y,x devono essere compresi tra -1.0 e 1.0, le coordinate che sono al di fuori di questo range non saranno visibili

Quello che si limita il programmatore è quello di specificare coordinate dentro un range che nel vertex shader verranno trasformate in coordinate NDC (normalized device coordinates), di seguito saranno date in input al rasterizer per trasformarle in coordinate 2d

Tutto questo processo inizia da:
- trasformare i vertici dell'oggetto in un insieme di sistemi di riferimento
- trasformazione delle coordinate in NDC

Ci sono delle trasformazioni intermedie perchè alcune operazioni sono più facili da computare con certi sistemi di riferimento