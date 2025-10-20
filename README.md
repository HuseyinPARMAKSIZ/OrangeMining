Windows 11'de Orange mining 3.39 kurulumu için Python 3.12 gereklidir. https://github.com/SHTOOLS/SHTOOLS/issues/494 nedenden dolayı Python 3.13 ile kurulum sonrası add-ons yükleme problemleri yaşanmaktadır.
Microsoft Visual Studio C++ 2015-2019 Redistributable x86 ve x64 14.23.27820 sürümleri gereklidir. Varsa 14- tüm sürümler çakışma olmaması adına kaldırılmalıdır.
AI Agent mantığını çizdiğimiz https://excalidraw.com/#json=A7ur1mHO81SRDEnfTRvfB,AJkGFC8-ZVbGokoi3oIw-Q yapısı mevcuttur.

Scopus'tan analiz amacıyla aşağıdaki query ve sayılarda akademik çalışma bilgileri CSV olarak indirilmiştir.
Document • 2325 documents
TITLE-ABS-KEY ( ("Orange" AND ("data mining" OR "machine learning" or "cybersecurity" or "social engineering")) OR "WEKA" OR "KNIME" OR "RapidMiner" ) AND PUBYEAR &gt; 2013 AND PUBYEAR &lt; 2025 AND ( LIMIT-TO ( DOCTYPE,"ar" ) ) AND ( LIMIT-TO ( LANGUAGE,"English" ) )

Document • 2400 documents
TITLE-ABS-KEY ( ( "Apache Superset" OR "Metabase" OR "Lightdash" OR "Redash" OR "Power BI" OR "Tableau" ) ) AND PUBYEAR &gt; 2014 AND PUBYEAR &lt; 2027 AND ( LIMIT-TO ( DOCTYPE,"ar" ) ) AND ( LIMIT-TO ( LANGUAGE,"English" ) )

Bu iki farklı CSV dosyasına ait Abstrast + Title + Keywords alanları Corpus olarak berlirlendikten sonra ilgili .ows dosyaları üzerinden analizler yapılabilmektedir. 

Stopwords Github sayfasında English stopwords indiirlmiş ve sonrasında eksik kısımlar manuel (Elsevier, based, ... gibi) oluşturulmuştur. 
