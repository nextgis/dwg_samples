# dwg_samples
AutoCAD DWG samples


#Types of objects
OpenDesign specification lists 78 types of objects ((page 102)[https://www.opendesign.com/files/guestdownloads/OpenDesign_Specification_for_.dwg_files.pdf])

* point - точка, vertex 3D (point)
* line - отрезок, 2 vertex 3D (polyline_line)

  ```_LINE 50,50 100,100  ```   
  
* arc - дуга, 2 vertex 3D + средняя точка и дуговой сегмент (не путать с дуговым сегментом полилинии)
* circle - окружность
* ellipse - эллипс
* polyline-2D-line - 2 и более 2D vertex, line сегменты
* polyline-2D-arc - 2 и более 2D vertex, arc сегменты
* polyline-3D-line - 2 и более 3D vertex, line сегменты
* polyline (mesh) - 
* polyline (pface) - 
* spline - 

#Formats

* 2000
* 2004
* 2007
* 2010
* 2013
* R14
