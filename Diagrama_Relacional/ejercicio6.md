<img width="490" height="490" alt="6 drawio (1)" src="https://github.com/user-attachments/assets/5f248c15-92e0-4be6-a5fe-11c89ca8dd9a" />

```.xml

<mxfile host="app.diagrams.net">
<diagram name="Página-1" id="mA0WMilzxsTCr6zGbYwX">
<mxGraphModel dx="1036" dy="540" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0" adaptiveColors="auto">
<root>
<mxCell id="0"/>
<mxCell id="1" parent="0"/>
<mxCell id="cliente" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;fontSize=14;" value="Cliente(<u>Id</u>, nombre, apellidos, dirección)" vertex="1">
<mxGeometry height="40" width="320" x="60" y="50" as="geometry"/>
</mxCell>
<mxCell id="telefono" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;fontSize=14;" value="Telefono_celular(<u>teléfono</u>, <u>id</u>)" vertex="1">
<mxGeometry height="40" width="320" x="20" y="120" as="geometry"/>
</mxCell>
<mxCell id="compra" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;fontSize=14;" value="Compra(fecha, id, código)" vertex="1">
<mxGeometry height="40" width="320" x="10" y="250" as="geometry"/>
</mxCell>
<mxCell id="producto" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;fontSize=14;" value="Producto(<u>Código</u>, descripción, precio, número_existencias)" vertex="1">
<mxGeometry height="40" width="390" x="80" y="180" as="geometry"/>
</mxCell>
<mxCell id="suministra" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;fontSize=14;" value="Suministra(código, Identificador)" vertex="1">
<mxGeometry height="40" width="320" x="30" y="460" as="geometry"/>
</mxCell>
<mxCell id="proveedor" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;fontSize=14;" value="Proveedor(<u>Identificador</u>, nombres, apellidos, dirección, provincia)" vertex="1">
<mxGeometry height="40" width="420" x="80" y="330" as="geometry"/>
</mxCell>
<mxCell id="numtel" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;fontSize=14;" value="Num_telefono(<u>celular</u>, <u>identificador</u>)" vertex="1">
<mxGeometry height="40" width="320" x="40" y="395" as="geometry"/>
</mxCell>
<mxCell id="e1" edge="1" parent="1" source="telefono" style="curved=1;html=1;endArrow=classic;strokeColor=#333333;strokeWidth=1.5;exitX=0.75;exitY=0;exitDx=0;exitDy=0;entryX=0.282;entryY=0.982;entryDx=0;entryDy=0;entryPerimeter=0;" target="cliente" value="">
<mxGeometry relative="1" as="geometry"/>
</mxCell>
<mxCell id="e3" edge="1" parent="1" source="compra" style="curved=1;html=1;endArrow=classic;strokeColor=#333333;strokeWidth=1.5;exitX=0.688;exitY=0.25;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0.25;entryY=1;entryDx=0;entryDy=0;" target="producto" value="">
<mxGeometry relative="1" as="geometry"/>
</mxCell>
<mxCell id="e4" edge="1" parent="1" source="numtel" style="curved=1;html=1;endArrow=classic;strokeColor=#333333;strokeWidth=1.5;exitX=0.75;exitY=0;exitDx=0;exitDy=0;entryX=0.25;entryY=1;entryDx=0;entryDy=0;" target="proveedor" value="">
<mxGeometry relative="1" as="geometry"/>
</mxCell>
<UserObject label="" mermaidId="e:Autor->Libro#0" mermaidBaseStyle="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;exitX=0.5;exitY=0.99;entryX=0.5;entryY=0;strokeWidth=2;targetPerimeterSpacing=4;" mermaidBaseValue="" id="L5HDaqyWzqlDtWksIbAl-1">
<mxCell edge="1" parent="1" source="suministra" style="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;strokeWidth=2;targetPerimeterSpacing=4;entryX=0.287;entryY=0.972;entryDx=0;entryDy=0;exitX=0.75;exitY=0;exitDx=0;exitDy=0;entryPerimeter=0;" target="proveedor">
<mxGeometry relative="1" x="-0.1433" as="geometry">
<Array as="points">
<mxPoint x="270" y="450"/>
<mxPoint x="450" y="450"/>
<mxPoint x="450" y="390"/>
<mxPoint x="200.5" y="390"/>
</Array>
<mxPoint x="614" y="435" as="sourcePoint"/>
<mxPoint x="449.99999999999994" y="474" as="targetPoint"/>
</mxGeometry>
</mxCell>
</UserObject>
<UserObject label="" mermaidId="e:Autor->Libro#0" mermaidBaseStyle="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;exitX=0.5;exitY=0.99;entryX=0.5;entryY=0;strokeWidth=2;targetPerimeterSpacing=4;" mermaidBaseValue="" id="L5HDaqyWzqlDtWksIbAl-2">
<mxCell edge="1" parent="1" style="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;strokeWidth=2;targetPerimeterSpacing=4;entryX=0.284;entryY=-0.002;entryDx=0;entryDy=0;entryPerimeter=0;" target="cliente">
<mxGeometry relative="1" x="-0.8737" as="geometry">
<Array as="points">
<mxPoint x="190" y="230"/>
<mxPoint x="50" y="230"/>
<mxPoint x="50" y="20"/>
<mxPoint x="150.9" y="20"/>
</Array>
<mxPoint x="190" y="240" as="sourcePoint"/>
<mxPoint y="269" as="targetPoint"/>
</mxGeometry>
</mxCell>
</UserObject>
<UserObject label="" mermaidId="e:Autor->Libro#0" mermaidBaseStyle="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;exitX=0.5;exitY=0.99;entryX=0.5;entryY=0;strokeWidth=2;targetPerimeterSpacing=4;" mermaidBaseValue="" id="L5HDaqyWzqlDtWksIbAl-3">
<mxCell edge="1" parent="1" source="suministra" style="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;strokeWidth=2;targetPerimeterSpacing=4;entryX=0.25;entryY=0;entryDx=0;entryDy=0;exitX=0.481;exitY=0.104;exitDx=0;exitDy=0;exitPerimeter=0;" target="producto">
<mxGeometry relative="1" x="-0.9411" as="geometry">
<Array as="points">
<mxPoint x="183.9" y="450"/>
<mxPoint x="20" y="450"/>
<mxPoint x="20" y="160"/>
<mxPoint x="177.5" y="160"/>
</Array>
<mxPoint x="184" y="440" as="sourcePoint"/>
<mxPoint x="20" y="479" as="targetPoint"/>
</mxGeometry>
</mxCell>
</UserObject>
<mxCell id="L5HDaqyWzqlDtWksIbAl-5" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Matias Romero 3A" vertex="1">
<mxGeometry height="30" width="130" x="348" y="20" as="geometry"/>
</mxCell>
</root>
</mxGraphModel>
</diagram>
</mxfile>
