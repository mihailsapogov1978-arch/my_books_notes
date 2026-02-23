```dataview
    LIST FROM "Философия/Авторы/Монтень_Мишель"
    WHERE file.name != this.file.name AND file.ext = "md"
    SORT file.name