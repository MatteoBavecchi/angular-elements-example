# AngularElementExample

Questo è un progetto esempio per creare un nuovo angular element

## Come è fatto

Si è creato l'app con il comando `ng new app`.

Successivamente con il comando `ng add @angular/elements` si è installato le dipendenze e i polyfills.

Nell' App Module si è aggiunto nel metodo NgDoBootstrap() i comandi per definire un nuovo custom element.


## Usare il componente
 
* Compilare l'app con il comando `ng build --prod --output-hashing none`
* Copiare il contenuto della cartella app/dist nella cartella del progetto che ospiterà l'angular element
* Aggiungere i file js come fatto nell' index.html di questo progetto.
* Se si include l'elemento in un altro progetto angular, si deve aggiungere `  schemas: [
    CUSTOM_ELEMENTS_SCHEMA
  ],` nell' App Module
