Ementa
=================================================

Aqui deixamos uma explicação da ementa do curso.

-------------------------------------------------
Aula 01 - Instalação
-------------------------------------------------

Nesta aula introdutória iremos instalar nossas ferramentas 
de trabalho. A aula irá cobrir a instalação do PostgreSQL
e do PostGIS em ambiente linux, incluindo a compilação de dependências externas, como GEOS, PROJ4 e libxml.

Além de instalar o PostGIS, iremos importar alguns dados e criar
algumas tabelas, só para molharmos nossos pés.

* Instalação do PostgreSQL;
* Instalação do PostGIS e dependências;
* Conversão de dados legado (shp2pgsql);
* Construção de tabelas geoespaciais;

-------------------------------------------------
Aula 02 - Baby Steps
-------------------------------------------------

Esta aula é importante para todos os alunos,m pois nela definiremos
uma porção de conceitos, entre eles os tipos geoespaciais (GEOMETRY e GEOGRAPHY), bem como nossos tipos de geometrias e sistemas de referência.

* Como funciona o PostGIS?

* Tabelas/views especiais;
	
	* geometry_columns;
	* geography_columns;
	* spatial_ref_sys;

* Tipos geométricos;
	* Ponto;
	* Linha;
	* Polígono;
	* Multi*;
	* Raster;

* Sistemas de Referência;

	* Como definir um sistema de referência;
	* Como converter dados de um SR para outro?

* Geometry;

* Geography;

-------------------------------------------------
Aula 03 - Funções Geoespaciais
-------------------------------------------------

Esta aula apresentará de forma prática diversas funções
presentes no PostGIS. Aqui apresentaremos a caixa de ferramentas
da extensão e testaremos com alguns dados de entrada.

* Gerenciamento

	* AddGeometryColumn;
	* DropGeometryColumn;
	* DropGeometryTable;
	* PostGIS_Full_Version;
	* Populate_Geometry_Columns;
	* UpdateGeometrySRID;

* Entrada

	* ST_GeomFromText;
	* ST_MakePoint;
	* ST_MakeLine;
	* ST_MakePolygon;
	* ST_MakeBox2D;
	* ST_GeogFromText;

* Propriedades Geométricas

	* ST_GeometryType;
	* ST_Envelope;
	* ST_Boundary;
	* ST_IsValid;
	* ST_IsValidReason;
	* ST_IsValidDetail;
	* ST_NPoints;
	* ST_PointN;
	* ST_StartPoint;
	* ST_EndPoint;
	* ST_SRID;
	* ST_X;
	* ST_Y;
	* ST_Z;
	* ST_M;

* Edição

	* ST_AddPoint;
	* ST_Force_2D, ST_Force_3D, ST_Force_3DZ, ST_Force_3DM;
	* ST_Force_Collection;
	* ST_LineMerge;
	* ST_Multi;
	* ST_SetSRID;
	* ST_Segmentize;
	* ST_Transform;
	* ST_Translate;

* Saída

	* ST_AsEWKB;
	* ST_AsWKB;
	* ST_AsText;
	* ST_GeoHash;

* Métrica

	* ST_Distance;
	* ST_Distance_Sphere;
	* ST_Distance_Spheroid;
	* ST_MaxDistance;
	* ST_Area;
	* ST_Perimeter;
	* ST_Length , ST_Length2D,ST_3DLength
	* ST_Centroid;
	* ST_Azimuth;

* Relacionamento

	* ST_Intersects;
	* ST_DWithin;
	* ST_DFullyWithin;
	* ST_Equals;
	* ST_OrderingEquals;
	* ST_Overlaps;
	* ST_Touches;
	* ST_Within;
	* ST_Contains;
	* ST_Covers;
	* ST_CoveredBy;
	* ST_Crosses;
	* ST_Disjoint;

* Processamento

	* ST_Intersection;
	* ST_Buffer;
	* ST_Collect;
	* ST_OffsetCurve;
	* ST_Split;
	* ST_Union;
	

-------------------------------------------------
Aula 04 - Funções Geoespaciais
-------------------------------------------------