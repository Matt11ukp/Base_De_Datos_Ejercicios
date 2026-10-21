<img width="576" height="400" alt="8 drawio (1)" src="https://github.com/user-attachments/assets/a51f4565-9421-4d5c-b1fc-885ee09380c5" />

```.xml

<mxfile host="app.diagrams.net">
<diagram name="Página-1" id="P6L4IOThKg3rryByZ8bI">
<mxGraphModel dx="807" dy="1590" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0" adaptiveColors="auto">
<root>
<mxCell id="0"/>
<mxCell id="1" parent="0"/>
<mxCell id="2" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;fontSize=14;" value="Provincia(<u>código</u>, nombre)" vertex="1">
<mxGeometry height="50" width="240" x="50" y="70" as="geometry"/>
</mxCell>
<mxCell id="3" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;fontSize=14;" value="Destinatario(<u>id_destinatario</u>, nombre, dirección)" vertex="1">
<mxGeometry height="60" width="370" x="44" y="140" as="geometry"/>
</mxCell>
<mxCell id="4" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;fontSize=14;" value="Paquete(<u>código</u>, descripción, dirección, código, id_destinatario, cédula)" vertex="1">
<mxGeometry height="80" width="470" x="70" y="-20" as="geometry"/>
</mxCell>
<mxCell id="5" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;fontSize=14;" value="Camionero(<u>Cédula</u>, nombre, teléfono, dirección)" vertex="1">
<mxGeometry height="60" width="340" x="60" y="215" as="geometry"/>
</mxCell>
<mxCell id="6" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;fontSize=14;" value="Camión(<u>matrícula</u>, modelo, potencia, tipo, cédula)" vertex="1">
<mxGeometry height="60" width="380" x="50" y="290" as="geometry"/>
</mxCell>
<mxCell id="e2" edge="1" parent="1" source="4" style="endArrow=classic;strokeColor=#333333;strokeWidth=1.5;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.617;exitY=0.75;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" target="2" value="">
<mxGeometry relative="1" x="0.9906" as="geometry">
<Array as="points">
<mxPoint x="170" y="50"/>
</Array>
</mxGeometry>
</mxCell>
<mxCell id="e3" edge="1" parent="1" source="4" style="endArrow=classic;strokeColor=#333333;strokeWidth=1.5;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.787;exitY=0.625;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0.422;entryY=0.167;entryDx=0;entryDy=0;entryPerimeter=0;" target="3" value="">
<mxGeometry relative="1" as="geometry">
<Array as="points">
<mxPoint x="439.9" y="120"/>
<mxPoint x="200.1" y="120"/>
</Array>
</mxGeometry>
</mxCell>
<mxCell id="p_rkfHmod5yqu25EOCx8-6" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="<font style="font-size: 18px;">Matias Romero 3A</font>" vertex="1">
<mxGeometry height="50" width="170" x="450" y="-50" as="geometry"/>
</mxCell>
<mxCell id="p_rkfHmod5yqu25EOCx8-7" edge="1" parent="1" source="4" style="endArrow=classic;strokeColor=#333333;strokeWidth=1.5;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.324;entryY=0.083;entryDx=0;entryDy=0;entryPerimeter=0;exitX=0.936;exitY=0.625;exitDx=0;exitDy=0;exitPerimeter=0;" target="5" value="">
<mxGeometry relative="1" x="-0.0296" as="geometry">
<Array as="points">
<mxPoint x="509.9" y="200"/>
<mxPoint x="170.2" y="200"/>
</Array>
<mxPoint x="490" y="90" as="sourcePoint"/>
<mxPoint x="380" y="260" as="targetPoint"/>
</mxGeometry>
</mxCell>
<mxCell id="p_rkfHmod5yqu25EOCx8-8" edge="1" parent="1" source="6" style="endArrow=classic;strokeColor=#333333;strokeWidth=1.5;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.845;exitY=0.167;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0.353;entryY=0.75;entryDx=0;entryDy=0;entryPerimeter=0;" target="5" value="">
<mxGeometry relative="1" x="0.9907" as="geometry">
<Array as="points">
<mxPoint x="371.1" y="285"/>
<mxPoint x="180" y="285"/>
</Array>
<mxPoint x="370" y="275" as="sourcePoint"/>
<mxPoint x="180" y="305" as="targetPoint"/>
</mxGeometry>
</mxCell>
</root>
</mxGraphModel>
</diagram>
</mxfile>
