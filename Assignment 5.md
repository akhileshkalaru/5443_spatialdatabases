	
			Assignment 5
File Extensions
(1)	SHP FILE:-
Shapefile is a popular geospatial vector data format for geographic information system software. It is developed and regulated by Esri as a (mostly) open specification for data interoperability among Esri and other GIS software products.  Shapefiles spatially describe vector features: points, lines, and polygons.
(2)	OSM FILE:-
This driver reads OpenStreetMap files, in .osm (XML based) and .pbf (optimized binary) formats. The driver is available if GDAL is built with SQLite support and, for .osm XML files, with Expat support. The filenames must end with .osm or .pbf extension.	
The driver will categorize features into 5 layers :
•	points : "node" features that have significant tags attached.
•	lines : "way" features that are recognized as non-area.
•	multilinestrings : "relation" features that form a multilinestring(type = 'multilinestring' or type = 'route').
•	multipolygons : "relation" features that form a multipolygon (type = 'multipolygon' or type = 'boundary'), and "way" features that are recognized as area.
•	other_relations : "relation" features that do not belong to the above 2 layers.

(3)	GEOJSON FILE:-
GeoJSON is a format for encoding a variety of geographic data structures. A GeoJSON object may represent a geometry, a feature, or a collection of features. GeoJSON supports the following geometry types: Point, LineString, Polygon, MultiPoint, MultiLineString, MultiPolygon, and GeometryCollection. Features in GeoJSON contain a geometry object and additional properties, and a feature collection represents a list of features. A complete GeoJSON data structure is always an object (in JSON terms). In GeoJSON, an object consists of a collection of name/value pairs -- also called members. For each member, the name is always a string. Member values are either a string, number, object, array or one of the literals: true, false, and null. An array consists of elements where each element is a value as described above.
(4)	GPX FILE:-
GPX (the GPS Exchange Format) is a light-weight XML data format for the interchange of GPS data (waypoints, routes, and tracks) between applications and Web services on the Internet. Its tags store location, elevation, and time and can in this way be used to interchange data between GPS devices and software packages. Such computer programs allow users, for example, to view th
eir tracks, project their tracks on satellite images or other maps, annotate maps, and tag photographs with the geolocation in the Exif metadata.
(5)	KML FILE:-
KML is a file format used to display geographic data in an Earth browser such as Google Earth, Google Maps, and Google Maps for mobile. KML uses a tag-based structure with nested elements and attributes and is based on the XML standard. All tags are case-sensitive and must appear exactly as they are listed in the KML Reference. The Reference indicates which tags are optional. Within a given element, tags must appear in the order shown in the Reference.
(6)	NMEA FILE:-
The National Marine Electronics Association (NMEA) has developed a specification that defines the interface between various pieces of marine electronic equipment. The standard permits marine electronics to send information to computers and to other marine equipment. A full copy of this standard is available for purchase at their web site. None of the information on this site comes from this standard and I do not have a copy. Anyone attempting to design anything to this standard should obtain an official copy.
GPS receiver communication is defined within this specification. Most computer programs that provide real time position information understand and expect data to be in NMEA format. This data includes the complete PVT (position, velocity, time) solution computed by the GPS receiver. The idea of NMEA is to send a line of data called a sentence that is totally self contained and independent from other sentences. There are standard sentences for each device category and there is also the ability to define proprietary sentences for use by the individual company. All of the standard sentences have a two letter prefix that defines the device that uses that sentence type. (For gps receivers the prefix is GP.) which is followed by a three letter sequence that defines the sentence contents. In addition NMEA permits hardware manufactures to define their own proprietary sentences for whatever purpose they see fit. All proprietary sentences begin with the letter P and are followed with 3 letters that identifies the manufacturer controlling that sentence. For example a Garmin sentence would start with PGRM and Magellan would begin with PMGN.
(7)	CSV FILE:-
A CSV is a comma separated values file, which allows data to be saved in a table structured format. CSVs look like a garden-variety spreadsheet but with a .csv extension (Traditionally they take the form of a text file containing information separated by commas, hence the name). CSV files can be used with any spreadsheet program, such as Microsoft Excel, Open Office Calc, or Google Spreadsheets. They differ from other spreadsheet file types in that you can only have a single sheet in a file, they cannot save cell, column, or row styling, and cannot save formulas.


(8)	WKT FILE:-
Well-known text (WKT) is a text markup language for representing vector geometry objects on a map, spatial reference systems of spatial objects and transformations between spatial reference systems. A binary equivalent, known as well-known binary (WKB) is used to transfer and store the same information on databases, such as PostGIS, Microsoft SQL Server and DB2. The formats were originally defined by the Open Geospatial Consortium (OGC) and described in their Simple Feature Access and Coordinate Transformation Service specifications.

SOFTWARES
(1)	ARCGIS:-
ArcGIS is a geographic information system (GIS) for working with maps and geographic information. It is used for: creating and using maps; compiling geographic data; analyzing mapped information; sharing and discovering geographic information; using maps and geographic information in a range of applications; and managing geographic information in a database.
The system provides an infrastructure for making maps and geographic information available throughout an organization, across a community, and openly on the Web.

(2)	QGIS:-

QGIS is a popular open-source GIS with advanced capabilities. Here is a series of tutorials and tips that show you how to use it to tackle common GIS problems.

(3)	GPSBABEL:-

GPSBabel is a handy tool that can convert the various data formats to the desired GPX format. GPSBabel is a command line application run from a console window or command shell.

(4)	 GDAL:-
GDAL (Geospatial Data Abstraction Library) is a library for reading and writing raster geospatial data formats, and is released under the permissive X/MIT style free software license by the Open Source Geospatial Foundation. As a library, it presents a single abstract data model to the calling application for all supported formats. It may also be built with a variety of useful command-line utilities for data translation and processing.
The related OGR library (OGR Simple Features Library), which is part of the GDAL source tree, provides a similar capability for simple features vector data.
GDAL was primarily developed by Frank Warmerdam until the release of version 1.3.2, when maintainership was officially transferred to the GDAL/OGR Project Management Committee under the Open Source Geospatial Foundation.
GDAL/OGR is considered a major free software project for its "extensive capabilities of data exchange" and also in the commercial GIS community due to its widespread use and comprehensive set of functionalities

DEFINATIONS
(1)	POINT:-
A point is an exact position or location on a plane surface. It is important to understand that a point is not a thing, but a place. We indicate the position of a point by placing a dot with a pencil. This dot may have a diameter of, say, 0.2mm, but a point has no size. No matter how far you zoomed in, it would still have no width. Since a point is a place, not a thing, it has no dimensions.
(2)	CURVE:-
In mathematics, a curve (also called a curved line in older texts) is, generally speaking, an object similar to a line but which is not required to be straight. This entails that a line is a special case of curve, namely a curve with null curvature.[1] Often curves in two-dimensional (plane curves) or three-dimensional (space curves) Euclidean space are of interest.
Various disciplines within mathematics have given the term different meanings depending on the area of study, so the precise meaning depends on context. However many of these meanings are special instances of the definition which follows. A curve is a topological space which is locally homeomorphic to a line. In everyday language, this means that a curve is a set of points which, near each of its points, looks like a line, up to a deformation. A simple example of a curve is the parabola, shown to the right. A large number of other curves have been studied in multiple mathematical fields.
(3)	LINESTRING:-
A linestring is a Curve with linear interpolation between Points.

(4)	MULTICURVE:-
The multi-curves framework is often implemented in a way to recycle to one curve formulas; there are no fundamental reasons behind that choice. Here we present different approaches to the multi-curves framework. They vary by the choice of building blocks instruments

(5)	MULTILINESTRING:-
Relations of type multilinestring are used to represent one on the ground feature made of one or multiple line strings made of even more ways compatible and as define by the Open Geospatial Consortium.
(6)	SURFACE POLYGONS:-
A polygonal surface can be thought of as a surface composed of polygonal faces. The polygons must all be of the same type (triangles, quadrilaterals or whatever).If the polygons are of higher order than triangles, the user must take care that the vertices of each polygon all lie in a plane. Otherwise, no planar polygon will pass through the vertices. If the nonplanarity is significant, then the display will not look right at all.

(7)	MULTIPOLYGONS:-
A MultiPolygon instance is a collection of zero or more Polygon instances. The boundary is defined by the two exterior rings and the three interior rings. The boundary is defined by the two exterior rings and the three interior rings. The two Polygon elements intersect at a tangent point.

			RELATIONSHIPS
(1)	TOUCHES:-
Touch returns t (TRUE) if none of the points common to both geometries intersect the interiors of both geometries. At least one geometry must be a linestring, polygon, multilinestring, or multipolygon. 
Touch returns TRUE if either of the geometrys boundaries intersect or if only one of the geometrys interiors intersects the others boundary.
The pattern matrices show us that the touch predicate returns TRUE when the interiors of the geometry dont intersect and the boundary of either geometry intersects the others interior or boundary.
The touch predicate returns TRUE if the boundary of one geometry intersects the interior of the other but the interiors do not intersect. The touch predicate returns TRUE if the boundary of one geometry intersects the interior of the other but the interiors do not intersect. The touch predicate returns TRUE if the boundaries of both geometries intersect but the interiors do not.

(2)	CROSSES:-
Cross returns t (TRUE) if the intersection results in a geometry whose dimension is one less than the maximum dimension of the two source geometries and the intersection set is interior to both source geometries. Cross returns t (TRUE) for only multipoint/polygon, multipoint/linestring, linestring/linestring, linestring/polygon, and linestring/multipolygon comparisons. This cross predicate pattern matrix applies to multipoint/linestring, multipoint/multilinestring, multipoint/polygon, multipoint/multipolygon, linestring/polygon, and linestring/multipolygon. The
matrix states that the interiors must intersect and that at least the interior of the primary (geometry a) must intersect the exterior of the secondary (geometry b). This cross predicate matrix applies to linestring/linestring, linestring/multilinestring, and multilinestring/multilinestring. 
The matrix states that the dimension of the intersection of the interiors
must be 0 (intersect at a point). If the dimension of this intersection was 1 (intersect at a linestring) the cross predicate would return FALSE but the overlap predicate would return TRUE.
(3)	WITHIN:-
Within returns t (TRUE) if the first geometry is completely within the second geometry. Within tests for the exact opposite result of contains. 
Within returns t (TRUE) if the first geometry is completely inside the second geometry. The boundary and interior of the first geometry are not allowed to intersect the exterior of the second geometry and the first geometry may not equal the second geometry.
The within predicate pattern matrix states that the interiors of both geometries must intersect and that the interior and boundary of the primary geometry (geometry a) must not intersect the exterior of the secondary (geometry b).

(4)	OVERLAPS:-
Overlap compares two geometries of the same dimension and returns t (TRUE) if their intersection set results in a geometry different from both but of the same dimension. Overlap returns t (TRUE) only for geometries of the same dimension and only when their intersection set results in a geometry of the same dimension. In other words, if the intersection of two polygons results in polygon, then overlap returns t (TRUE).
This pattern matrix applies to polygon/polygon, multipoint/multipoint and multipolygon/multipolygon overlays. For these combinations the overlap predicate returns TRUE if the interior of both geometries intersects the others interior and exterior. This pattern matrix applies to linestring/linestring and multilinestring/multilinestring overlaps. In this case the intersection of the geometries must result in a geometry that has a dimension of 1 (another linestring). If the dimension of the intersection of the interiors had resulted in 0 (a point) the overlap predicate would return FALSE; however, the cross predicate would have returned TRUE.








