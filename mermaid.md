```mermaid
gantt
    title WordPress Migration – LB2
    dateFormat  YYYY-MM-DD
    axisFormat  %d.%m.

    section Vorbereitung
    Repository erstellen        :done,    repo,    2025-05-15, 1d
    Bewertungsraster einfügen  :done,    raster,  2025-05-15, 1d
    FTP-Zugang testen           :done,    ftp,     2025-05-15, 1d

    section Backup
    Backup herunterladen        :active,  backup,  2025-05-16, 1d
    section Zielsystem
    
    section Migration
    Server installieren         :todo   ,    server,  2025-05-17, 1d




```