### >python .\pdf_splitter.py .\600x426_tpt.pdf --info


Información del PDF: .\600x426_tpt.pdf


Metadatos:
  Título: A2.indd
  Creador: Adobe InDesign CC 2015 (Macintosh)
  Productor: Adobe PDF Library 15.0

Número de páginas: 1

Dimensiones por página:
  Página 1: 426.00 mm x 600.00 mm (426.00 x 600.00 mm)

### > python.exe .\pdf_splitter.py .\600x426_tpt.pdf --vertical 4 --output-dir ./seccion

PDF: .\600x426_tpt.pdf
Dimensiones de página: 426.00mm x 600.00mm
Modo: Vertical (1 columnas)
Anchos: 4.0mm
Ancho total: 4.00mm (página: 426.00mm)
⚠ Advertencia: La suma de anchos difiere del ancho de página

Modo de salida: Múltiples archivos
Directorio de salida: ./seccion
Prefijo: 600x426_tpt

  Procesando página 1/1 (426.00mm x 600.00mm)
    ✓ Generado: 600x426_tpt_p1_v1.pdf


✓ Proceso completado. Archivos generados: 1
  - ./seccion\600x426_tpt_p1_v1.pdf

### >python .\pdf_splitter.py .\seccion\600x426_tpt_p1_v1.pdf --info

Metadatos:
  Productor: pypdf

Número de páginas: 1

Dimensiones por página:
  Página 1: 4.00 mm x 600.00 mm (4.00 x 600.00 mm)

### >python.exe .\pdf_splitter.py .\600x426_tpt.pdf --vertical 50 100 60 --output-dir ./columnas

PDF: .\600x426_tpt.pdf
Dimensiones de página: 426.00mm x 600.00mm
Modo: Vertical (3 columnas)
Anchos: 50.0mm, 100.0mm, 60.0mm
Ancho total: 210.00mm (página: 426.00mm)
⚠ Advertencia: La suma de anchos difiere del ancho de página

Modo de salida: Múltiples archivos
Directorio de salida: ./columnas
Prefijo: 600x426_tpt

  Procesando página 1/1 (426.00mm x 600.00mm)
    ✓ Generado: 600x426_tpt_p1_v1.pdf
    ✓ Generado: 600x426_tpt_p1_v2.pdf
    ✓ Generado: 600x426_tpt_p1_v3.pdf


✓ Proceso completado. Archivos generados: 3
  - ./columnas\600x426_tpt_p1_v1.pdf
  - ./columnas\600x426_tpt_p1_v2.pdf
  - ./columnas\600x426_tpt_p1_v3.pdf

### >python .\pdf_splitter.py .\columnas\600x426_tpt_p1_v1.pdf --info

Información del PDF: .\columnas\600x426_tpt_p1_v1.pdf

Metadatos:
  Productor: pypdf

Número de páginas: 1

Dimensiones por página:
  Página 1: 50.00 mm x 600.00 mm (50.00 x 600.00 mm)
