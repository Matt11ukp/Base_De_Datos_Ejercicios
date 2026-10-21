<img width="610" height="768" alt="9 drawio" src="https://github.com/user-attachments/assets/ca8899e7-35a6-4cec-88cf-325014d7c36a" />

```.xml

<mxfile host="app.diagrams.net">
<diagram name="Página-1" id="ODDY9MwRJlvJVWaTIE7G">
<mxGraphModel dx="1546" dy="806" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0" adaptiveColors="auto">
<root>
<mxCell id="0"/>
<mxCell id="1" parent="0"/>
<mxCell id="prop" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;strokeColor=none;fillColor=none;fontSize=14;" value="Propietario(<u>cédula</u>, nombres, dirección)" vertex="1">
<mxGeometry height="70" width="340" x="50" y="80" as="geometry"/>
</mxCell>
<mxCell id="tel" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;strokeColor=none;fillColor=none;fontSize=14;" value="Telefonos(<u>teléfono</u>, <u>cédula</u>)" vertex="1">
<mxGeometry height="70" width="340" x="10" y="170" as="geometry"/>
</mxCell>
<mxCell id="fam" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;strokeColor=none;fillColor=none;fontSize=14;" value="Familiar(<u>cédula</u>, nombres, cédula)" vertex="1">
<mxGeometry height="70" width="340" x="30" y="250" as="geometry"/>
</mxCell>
<mxCell id="mas" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;strokeColor=none;fillColor=none;fontSize=14;" value="Mascota(<u>id,&nbsp;</u>fecha_Nacimiento, nombre, tipo, cédula)" vertex="1">
<mxGeometry height="70" width="340" x="90" y="420" as="geometry"/>
</mxCell>
<mxCell id="telf" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;strokeColor=none;fillColor=none;fontSize=14;" value="Telf_familiar(<u>teléfono</u>, <u>cédula</u>)" vertex="1">
<mxGeometry height="70" width="340" x="10" y="340" as="geometry"/>
</mxCell>
<mxCell id="con" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;strokeColor=none;fillColor=none;fontSize=14;" value="Consulta(<u>fecha_atencion</u>, diagnostico, id, cédula)" vertex="1">
<mxGeometry height="70" width="340" x="74" y="500" as="geometry"/>
</mxCell>
<mxCell id="vet" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;strokeColor=none;fillColor=none;fontSize=14;" value="Veterinario(<u>Cédula</u>, nombre, código, fecha_alta, especialidad)" vertex="1">
<mxGeometry height="70" width="340" x="60" y="668" as="geometry"/>
</mxCell>
<mxCell id="per" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;strokeColor=none;fillColor=none;fontSize=14;" value="Personal(<u>cédula</u>, nombre, código)" vertex="1">
<mxGeometry height="70" width="340" x="20" y="584" as="geometry"/>
</mxCell>
<mxCell id="aux" parent="1" style="text;html=1;whiteSpace=wrap;align=center;verticalAlign=middle;strokeColor=none;fillColor=none;fontSize=14;" value="Auxiliar(<u>cédula</u>, nombre, código, base_cotización)" vertex="1">
<mxGeometry height="70" width="340" x="73" y="710" as="geometry"/>
</mxCell>
<mxCell id="ANym8h5rxpPm_UNm9PhH-1" edge="1" parent="1" source="tel" style="endArrow=classic;strokeColor=#333333;strokeWidth=1.5;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.412;entryY=0.714;entryDx=0;entryDy=0;exitX=0.676;exitY=0.286;exitDx=0;exitDy=0;exitPerimeter=0;entryPerimeter=0;" target="prop" value="">
<mxGeometry relative="1" x="0.9926" as="geometry">
<Array as="points"/>
<mxPoint x="240" y="160" as="sourcePoint"/>
<mxPoint x="50" y="190" as="targetPoint"/>
</mxGeometry>
</mxCell>
<mxCell id="ANym8h5rxpPm_UNm9PhH-2" edge="1" parent="1" source="fam" style="endArrow=classic;strokeColor=#333333;strokeWidth=1.5;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.411;entryY=0.286;entryDx=0;entryDy=0;exitX=0.735;exitY=0.286;exitDx=0;exitDy=0;exitPerimeter=0;entryPerimeter=0;" target="prop" value="">
<mxGeometry relative="1" x="0.9236" as="geometry">
<Array as="points">
<mxPoint x="279.9" y="260"/>
<mxPoint x="360" y="260"/>
<mxPoint x="360" y="30"/>
<mxPoint x="189.7" y="30"/>
</Array>
<mxPoint x="285" y="250" as="sourcePoint"/>
<mxPoint x="235" y="190" as="targetPoint"/>
</mxGeometry>
</mxCell>
<mxCell id="ANym8h5rxpPm_UNm9PhH-3" edge="1" parent="1" source="telf" style="endArrow=classic;strokeColor=#333333;strokeWidth=1.5;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.412;entryY=0.714;entryDx=0;entryDy=0;exitX=0.706;exitY=0.286;exitDx=0;exitDy=0;exitPerimeter=0;entryPerimeter=0;" value="">
<mxGeometry relative="1" x="1" as="geometry">
<Array as="points"/>
<mxPoint x="225" y="350" as="sourcePoint"/>
<mxPoint x="175" y="290" as="targetPoint"/>
</mxGeometry>
</mxCell>
<mxCell id="ANym8h5rxpPm_UNm9PhH-4" edge="1" parent="1" style="endArrow=classic;strokeColor=#333333;strokeWidth=1.5;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.382;entryY=0.286;entryDx=0;entryDy=0;exitX=0.735;exitY=0.286;exitDx=0;exitDy=0;exitPerimeter=0;entryPerimeter=0;" target="prop" value="">
<mxGeometry relative="1" x="0.8547" as="geometry">
<Array as="points">
<mxPoint x="400" y="430"/>
<mxPoint x="440" y="430"/>
<mxPoint x="440" y="20"/>
<mxPoint x="179.9" y="20"/>
</Array>
<mxPoint x="400" y="440" as="sourcePoint"/>
<mxPoint x="310" y="270" as="targetPoint"/>
</mxGeometry>
</mxCell>
<mxCell id="ANym8h5rxpPm_UNm9PhH-5" edge="1" parent="1" source="con" style="endArrow=classic;strokeColor=#333333;strokeWidth=1.5;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.782;exitY=0.286;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0.206;entryY=0.714;entryDx=0;entryDy=0;entryPerimeter=0;" target="mas" value="">
<mxGeometry relative="1" x="0.807" as="geometry">
<Array as="points">
<mxPoint x="339.9" y="500"/>
<mxPoint x="160" y="500"/>
</Array>
<mxPoint x="257.5" y="520" as="sourcePoint"/>
<mxPoint x="182.5" y="450" as="targetPoint"/>
</mxGeometry>
</mxCell>
<mxCell id="ANym8h5rxpPm_UNm9PhH-6" edge="1" parent="1" source="con" style="endArrow=classic;strokeColor=#333333;strokeWidth=1.5;edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.324;entryY=0.171;entryDx=0;entryDy=0;exitX=0.9;exitY=0.714;exitDx=0;exitDy=0;exitPerimeter=0;entryPerimeter=0;" target="vet" value="">
<mxGeometry relative="1" x="1" as="geometry">
<Array as="points">
<mxPoint x="380" y="640"/>
<mxPoint x="170.2" y="640"/>
</Array>
<mxPoint x="395" y="630" as="sourcePoint"/>
<mxPoint x="320" y="560" as="targetPoint"/>
</mxGeometry>
</mxCell>
<mxCell id="ANym8h5rxpPm_UNm9PhH-7" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="<font style="font-size: 18px;">Matias Romero 3A</font>" vertex="1">
<mxGeometry height="50" width="170" x="450" y="260" as="geometry"/>
</mxCell>
</root>
</mxGraphModel>
</diagram>
</mxfile>
