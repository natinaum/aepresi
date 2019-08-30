Pointer Arithmetik
==================
- Was ist Pointer Arithmetik
    - Allgemein 
    - In C
- Arithmetische Optionen
    - Zwischen Pointer
    - Zwischen Pointer und Ganzzahl
- Anwendungsbeispiele
    - Tauschen über Scopes hinweg
    - Iterriren durch Arrays
- Heap vs. Stack

Stack

    very fast access
    don't have to explicitly de-allocate variables
    space is managed efficiently by CPU, memory will not become fragmented
    local variables only
    limit on stack size (OS-dependent)
    variables cannot be resized

Heap

    variables can be accessed globally
    no limit on memory size
    (relatively) slower access
    no guaranteed efficient use of space, memory may become fragmented over time as blocks of memory are allocated, then freed
    you must manage memory (you're in charge of allocating and freeing variables)
    variables can be resized using realloc()


