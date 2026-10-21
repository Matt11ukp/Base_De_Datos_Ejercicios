<img width="411" height="350" alt="7 drawio (1)" src="https://github.com/user-attachments/assets/a1cb152f-3c65-4543-b1a0-ac8482f8ae40" />

```.xml

<mxfile host="app.diagrams.net">
<diagram name="Página-1" id="1QICsfwssStvYzIOS5wc">
<mxGraphModel dx="1098" dy="572" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0" adaptiveColors="auto">
<root>
<mxCell id="0"/>
<mxCell id="1" parent="0"/>
<mxCell id="gm" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;strokeColor=none;fillColor=none;fontSize=14;" value="Genero_Musical(<u>id</u>)" vertex="1">
<mxGeometry height="30" width="260" x="100" y="160" as="geometry"/>
</mxCell>
<mxCell id="disco" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;strokeColor=none;fillColor=none;fontSize=14;" value="Disco(<u>id</u>, titulo, precio, id, identificador)" vertex="1">
<mxGeometry height="30" width="380" x="100" y="90" as="geometry"/>
</mxCell>
<mxCell id="cant" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;strokeColor=none;fillColor=none;fontSize=14;" value="Cantante(Nombre, pais, <u>identificador</u>)" vertex="1">
<mxGeometry height="30" width="300" x="140" y="230" as="geometry"/>
</mxCell>
<mxCell id="tiene" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;strokeColor=none;fillColor=none;fontSize=14;" value="Tiene(id, identificador, posicion)" vertex="1">
<mxGeometry height="30" width="300" x="114" y="350" as="geometry"/>
</mxCell>
<mxCell id="cancion" parent="1" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;strokeColor=none;fillColor=none;fontSize=14;" value="Cancion(<u>Identificador</u>, titulo)" vertex="1">
<mxGeometry height="30" width="260" x="130" y="290" as="geometry"/>
</mxCell>
<mxCell id="e1" edge="1" parent="1" source="disco" style="curved=1;html=1;endArrow=classic;strokeColor=#333333;strokeWidth=1.5;entryX=0.713;entryY=0.089;entryDx=0;entryDy=0;entryPerimeter=0;exitX=0.569;exitY=0.92;exitDx=0;exitDy=0;exitPerimeter=0;" target="gm" value="">
<mxGeometry relative="1" as="geometry"/>
</mxCell>
<mxCell id="e4" edge="1" parent="1" source="tiene" style="curved=1;html=1;endArrow=classic;strokeColor=#333333;strokeWidth=1.5;" target="cancion" value="">
<mxGeometry relative="1" as="geometry"/>
</mxCell>
<UserObject label="" mermaidId="e:Autor->Libro#0" mermaidBaseStyle="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;exitX=0.5;exitY=0.99;entryX=0.5;entryY=0;strokeWidth=2;targetPerimeterSpacing=4;" mermaidBaseValue="" id="CRdl4nqRombtQX8UYNAD-1">
<mxCell edge="1" parent="1" source="tiene" style="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;strokeWidth=2;targetPerimeterSpacing=4;exitX=0.309;exitY=-0.067;exitDx=0;exitDy=0;exitPerimeter=0;">
<mxGeometry relative="1" x="-0.4838" as="geometry">
<Array as="points">
<mxPoint x="206.7" y="320"/>
<mxPoint x="89" y="320"/>
<mxPoint x="89" y="271"/>
<mxPoint x="90" y="271"/>
<mxPoint x="90" y="40"/>
<mxPoint x="220" y="40"/>
</Array>
<mxPoint x="89" y="341" as="sourcePoint"/>
<mxPoint x="220" y="80" as="targetPoint"/>
</mxGeometry>
</mxCell>
</UserObject>
<mxCell id="CRdl4nqRombtQX8UYNAD-2" edge="1" parent="1" source="disco" style="curved=1;html=1;endArrow=classic;strokeColor=#333333;strokeWidth=1.5;entryX=0.777;entryY=-0.074;entryDx=0;entryDy=0;entryPerimeter=0;exitX=0.712;exitY=1.003;exitDx=0;exitDy=0;exitPerimeter=0;" target="cant" value="">
<mxGeometry relative="1" as="geometry">
<mxPoint x="381" y="153" as="sourcePoint"/>
<mxPoint x="350" y="198" as="targetPoint"/>
</mxGeometry>
</mxCell>
<mxCell id="CRdl4nqRombtQX8UYNAD-3" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Matias Romero 3A" vertex="1">
<mxGeometry height="30" width="130" x="360" y="40" as="geometry"/>
</mxCell>
</root>
</mxGraphModel>
</diagram>
</mxfile>
