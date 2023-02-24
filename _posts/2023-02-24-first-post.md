---
title: Tytul
date: 24.02.2023 11:52 -500
categories: [kategoria1, kategoria2]
tags: [tag1, tag2]
---

# Welcome kurwa

Siema siema witam w dokumentacji!

Donec sit amet erat non lorem convallis feugiat vitae nec eros.
Donec eleifend lacinia dui ac vulputate. Nulla et efficitur ex. 
Cras molestie convallis hendrerit. Aliquam urna quam, congue vel odio eget, auctor cursus nunc.
Integer aliquet lacinia ante. Vestibulum leo ligula, varius elementum placerat a, pulvinar elementum lacus.
Sed hendrerit eros est, sed lacinia nunc ornare sit amet. Quisque a velit egestas, molestie odio at, ornare tortor.
Fusce eu lectus dapibus, facilisis odio sed, sagittis tortor. Fusce est tellus, aliquam in tortor a, finibus facilisis massa. 
Duis rhoncus fermentum ligula. Aenean gravida at arcu ut eleifend. Praesent suscipit venenatis orci ac elementum.

## Jakis inny header

Donec sit amet erat non lorem convallis feugiat vitae nec eros.
Donec eleifend lacinia dui ac vulputate. Nulla et efficitur ex.
Cras molestie convallis hendrerit. Aliquam urna quam, congue vel odio eget, auctor cursus nunc.
Integer aliquet lacinia ante. Vestibulum leo ligula, varius elementum placerat a, pulvinar elementum lacus.
Sed hendrerit eros est, sed lacinia nunc ornare sit amet. Quisque a velit egestas, molestie odio at, ornare tortor.
Fusce eu lectus dapibus, facilisis odio sed, sagittis tortor. Fusce est tellus, aliquam in tortor a, finibus facilisis massa.
Duis rhoncus fermentum ligula. Aenean gravida at arcu ut eleifend. Praesent suscipit venenatis orci ac elementum.
Donec sit amet erat non lorem convallis feugiat vitae nec eros.
Donec eleifend lacinia dui ac vulputate. Nulla et efficitur ex.
Cras molestie convallis hendrerit. Aliquam urna quam, congue vel odio eget, auctor cursus nunc.
Integer aliquet lacinia ante. Vestibulum leo ligula, varius elementum placerat a, pulvinar elementum lacus.
Sed hendrerit eros est, sed lacinia nunc ornare sit amet. Quisque a velit egestas, molestie odio at, ornare tortor.
Fusce eu lectus dapibus, facilisis odio sed, sagittis tortor. Fusce est tellus, aliquam in tortor a, finibus facilisis massa.
Duis rhoncus fermentum ligula. Aenean gravida at arcu ut eleifend. Praesent suscipit venenatis orci ac elementum.

### Jeszcze inny mniej istotny

Donec sit amet erat non lorem convallis feugiat vitae nec eros.
Donec eleifend lacinia dui ac vulputate. Nulla et efficitur ex.
Cras molestie convallis hendrerit. Aliquam urna quam, congue vel odio eget, auctor cursus nunc.
Integer aliquet lacinia ante. Vestibulum leo ligula, varius elementum placerat a, pulvinar elementum lacus.
Sed hendrerit eros est, sed lacinia nunc ornare sit amet. Quisque a velit egestas, molestie odio at, ornare tortor.
Fusce eu lectus dapibus, facilisis odio sed, sagittis tortor. Fusce est tellus, aliquam in tortor a, finibus facilisis massa.
Duis rhoncus fermentum ligula. Aenean gravida at arcu ut eleifend. Praesent suscipit venenatis orci ac elementum.

* glupi
* glupszy
* najglupszy

```csharp
public class SetRandomColor : MonoBehaviour
{
    private SpriteRenderer _spriteRenderer;

    private void Awake() => _spriteRenderer = GetComponent<SpriteRenderer>();


    private void Update()
    {
        if (Input.GetButtonDown("Fire1"))
            _spriteRenderer.color = ChangeColor();
    }
    private Color ChangeColor()
    {
        return new Color(UnityEngine.Random.Range(0f, 1f),
            UnityEngine.Random.Range(0f, 1f),
            UnityEngine.Random.Range(0f, 1f));
    }
}
```

## Photos

![img-description](https://ocdn.eu/pulscms-transforms/1/Ii4k9kpTURBXy82NWMxYTJhYTgzOTRiNmU0ZjIwMDIzYmQ2NjViNDA0Ni5qcGeTlQMAzL_NF-vNDXSTBc0EsM0CpJMJpjQ0YjQxYQbeAAGhMAE/domowy-kebab-z-kurczaka-to-danie-ktore-bez-problemu-przygotujecie-samodzielnie-w-domu.jpeg)
