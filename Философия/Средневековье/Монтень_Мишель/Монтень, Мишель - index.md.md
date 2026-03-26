```dataview
    LIST FROM "Философия/Средневековье/Монтень_Мишель"
    WHERE file.name != this.file.name AND file.ext = "md"
    SORT file.name