# IAL-algorithns

C202: 


Implementujte abstraktní datový typ jednosměrný lineární seznam.

Vaším úkolem je implementovat následující operace, které spolu s výše
uvedenou datovou částí abstrakce tvoří abstraktní datový typ tList:

        DisposeList ... zrušení všech prvků seznamu,
        InitList ...... inicializace seznamu před prvním použitím,
        InsertFirst ... vložení prvku na začátek seznamu,
        First ......... nastavení aktivity na první prvek,
        CopyFirst ..... vrací hodnotu prvního prvku,
        DeleteFirst ... zruší první prvek seznamu,
        PostDelete .... ruší prvek za aktivním prvkem,
        PostInsert .... vloží nový prvek za aktivní prvek seznamu,
        Copy .......... vrací hodnotu aktivního prvku,
        Actualize ..... přepíše obsah aktivního prvku novou hodnotou,
        Succ .......... posune aktivitu na další prvek seznamu,
        Active ........ zjišťuje aktivitu seznamu.


C204: 

Implementujte frontu znaků v poli. 

Implementujte následující funkce:

      queueInit ..... inicializace fronty
      nextIndex ..... pomocná funkce - viz popis výše
      queueEmpty .... test na prázdnost fronty  
      queueFull ..... test, zda je fronta zaplněna (vyčerpána kapacita)
      queueFront .... přečte hodnoty prvního prvku z fronty
      queueRemove ... odstraní první prvek fronty
      queueGet ...... přečte a odstraní první prvek fronty  
      queueUp ....... zařazení prvku na konec fronty

C206: 

Implementujte abstraktní datový typ dvousměrně vázaný lineární seznam.

Vaším úkolem je implementovat následující operace, které spolu
s výše uvedenou datovou částí abstrakce tvoří abstraktní datový typ
obousměrně vázaný lineární seznam:

        DLInitList ...... inicializace seznamu před prvním použitím,
        DLDisposeList ... zrušení všech prvků seznamu,
        DLInsertFirst ... vložení prvku na začátek seznamu,
        DLInsertLast .... vložení prvku na konec seznamu,
        DLFirst ......... nastavení aktivity na první prvek,
        DLLast .......... nastavení aktivity na poslední prvek,
        DLCopyFirst ..... vrací hodnotu prvního prvku,
        DLCopyLast ...... vrací hodnotu posledního prvku,
        DLDeleteFirst ... zruší první prvek seznamu,
        DLDeleteLast .... zruší poslední prvek seznamu,
        DLPostDelete .... ruší prvek za aktivním prvkem,
        DLPreDelete ..... ruší prvek před aktivním prvkem,
        DLPostInsert .... vloží nový prvek za aktivní prvek seznamu,
        DLPreInsert ..... vloží nový prvek před aktivní prvek seznamu,
        DLCopy .......... vrací hodnotu aktivního prvku,
        DLActualize ..... přepíše obsah aktivního prvku novou hodnotou,
        DLPred .......... posune aktivitu na předchozí prvek seznamu,
        DLSucc .......... posune aktivitu na další prvek seznamu,
        DLActive ........ zjišťuje aktivitu seznamu.
