# dwg_samples
AutoCAD DWG samples. Produced with trial AutoCAD 2016 M.49.0.0


#Types of objects
OpenDesign specification lists 78 types of objects ((page 102)[https://www.opendesign.com/files/guestdownloads/OpenDesign_Specification_for_.dwg_files.pdf])

Each command should end with two spaces. New DWGs are created via New -> Open with no template - metric

* point2D - точка, vertex 2D (point)

  ```_POINT 50,50 ```  

* point3D - точка, vertex 3D (point)

  ```_POINT 50,50,50 ```  

* line - отрезок, 2 vertex 3D (polyline_line)

  ```_LINE 50,50 100,100  ```   
  
* arc - дуга, 2 vertex 3D + средняя точка и дуговой сегмент (не путать с дуговым сегментом полилинии)
  
  ```_ARC 50,50 75,75 100,50 ```

* circle - окружность
  
  ```_CIRCLE 50,50 50 ```

* ellipse - эллипс

  ```_ELLIPSE 50,50 150,150 30 ```

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
