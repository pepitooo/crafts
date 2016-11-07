# 3D objects with a laser cutter

In this example I will do an holder for drill bits.
I Bought in china some cheap drill bits, but it came without any case.
My goal will be to do a basic holder for drill bits to be easy accessible and well organized on my workbench.

## What do you need ?

1. laser cutter
2. material
3. [onshape](https://www.onshape.com/) account
4. [Kiri:Moto](https://grid.space/kiri) plugin
5. [qcad](http://www.qcad.org/)
6. time

## First designing our 3D object

I suggest you to follow an [onshape tutorial](https://www.onshape.com/videos/topic/tutorials) if you don't know how to do it. It's quite simple and easy to use.

### 2D Sketch

![image](./photo/sketch.png)

### Extrude top part
As my material is 3mm, I used a multiplier of 3, here 5*3, you can use arithmetic formula directly in onshape.
![image](./photo/extrude-top.png)

### Extrude bottom part
![image](./photo/extrude-bottom.png)

### Boolean union of the 2 extruded parts
![image](./photo/union-2-extruded-parts.png)

## Slicing with Kiri:Moto

### Opening plugin Kiri:Moto
If you don't have it, you can find it in the App Store of onshape, it's free.
![image](./photo/open-kiri-moto.png)

### Import your part
![image](./photo/kiri-moto-import-part.png)

### Setup Kiri moto for slicing
Select "Laser Cutting" mode, then on the right side of the screen you have few parameter to adjust to your material. My material is a MDF 3mm so I change layer height to 3
![image](./photo/kiri-moto-settings.png)

### Slice your object
Just click on Export on the left side, to save your file in somewhere in your computer, choose as dxf to be able to modify it.
![image](./photo/kiri-moto-slice-export.png)

## QCAD

### Edit with QCAD
With QCAD will add some mark to identify each bits.
The layer 0 is my layer for cutting, layer 1 is the one for marking.

Layer 0 (cutting) must have a width of 0mm, otherwise the laser cutter will just ignore it.

![image](./photo/qcad-marking.png)

### Final export for laser cutter
You can notice I re-organized my different material layer to fit to my raw material.

![image](./photo/qcad-export-pdf.png)

## Time to make real thing

### Laser cutter
Choose the right setting to cut your material and cut it.

![image](./photo/laser-cutted.jpeg)

### Assembly
To be a real 3D object you have to glue each parts together, and let it dry.

![image](./photo/assembled.jpeg)

## What you can do more with this method ?
I did this. All the plastic case was before I organized every thing with it. I don't tell you the nightmare to look for the the right bit and the right collet.
![image](./photo/what-i-did.jpeg)
