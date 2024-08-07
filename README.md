# SQL MIME Types

Данные представляют собой две SQL таблицы.

`mime_types_primary` - основные категории mime-типов
`mime_types_secondary` - более подробное описание mime-типов

### Колонки в таблице `mime_types_secondary`
- "primary_mime_id" - номер основной категории
- "type_name" - название типа
- "extension" - расширения типа (разделитель - *запятая*)
- "compressible" - возможность сжатия файла
