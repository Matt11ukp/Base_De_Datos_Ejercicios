<img width="595" height="281" alt="2 drawio" src="https://github.com/user-attachments/assets/56efb06e-7fd5-4ac0-a411-91f33465c63e" />

```.xml
<mxfile host="app.diagrams.net">
<diagram name="Página-1" id="wvJidXZe1gdvj1S6s3Aw">
<mxGraphModel dx="627" dy="327" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
<root>
<mxCell id="0"/>
<mxCell id="1" parent="0"/>
<UserObject label="" mermaidData="{ "data": "flowchart TB\n Socio[\"Socio (id_socio)\"]\n Libro[\"Libro (fecha_retiro, fecha_devolucion, id_socio, id_libro)\"]\n Autor[\"Autor (Id_Autor, id_libro)\"]\n Libro --> Socio\n Autor --> Libro\n style Socio fill:none,stroke:none,color:#000\n style Libro fill:none,stroke:none,color:#000\n style Autor fill:none,stroke:none,color:#000\n linkStyle default stroke:#000,fill:none", "config": null, "version": "12" }" id="LFypNAhggcB2WLTjAA__-1">
<mxCell connectable="0" parent="1" style="group;transparentBounds=1;editIcon=1;lockedGroup=0;groupPadding=10;" vertex="1">
<mxGeometry as="geometry"/>
</mxCell>
</UserObject>
<UserObject label="Pedido(<u>id_Pedido</u>, Precio, cantidad, id_cliente, id_mesero )" mermaidId="n:Socio" mermaidBaseStyle="html=1;whiteSpace=wrap;strokeWidth=2;fillColor=none;strokeColor=none;fontColor=default;fontFamily=Recursive;fontSize=14;shadow=1;shadowColor=#000000;shadowOffsetX=4;shadowOffsetY=4;shadowBlur=0;shadowOpacity=6;" mermaidBaseValue="Socio (id_socio)" id="LFypNAhggcB2WLTjAA__-2">
<mxCell parent="LFypNAhggcB2WLTjAA__-1" style="html=1;whiteSpace=wrap;strokeWidth=2;fillColor=none;strokeColor=none;fontColor=default;fontFamily=Recursive;fontSize=14;shadow=1;shadowColor=#000000;shadowOffsetX=4;shadowOffsetY=4;shadowBlur=0;shadowOpacity=6;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DRecursive;" vertex="1">
<mxGeometry height="45" width="550" x="35" y="110" as="geometry"/>
</mxCell>
</UserObject>
<UserObject label="Plato(<u>id_Plato</u>,precio_actual,id_pedido)" mermaidId="n:Libro" mermaidBaseStyle="html=1;whiteSpace=wrap;strokeWidth=2;fillColor=none;strokeColor=none;fontColor=default;fontFamily=Recursive;fontSize=14;shadow=1;shadowColor=#000000;shadowOffsetX=4;shadowOffsetY=4;shadowBlur=0;shadowOpacity=6;" mermaidBaseValue="Libro (fecha_retiro, fecha_devolucion, id_socio, id_libro)" id="LFypNAhggcB2WLTjAA__-3">
<mxCell parent="LFypNAhggcB2WLTjAA__-1" style="html=1;whiteSpace=wrap;strokeWidth=2;fillColor=none;strokeColor=none;fontColor=default;fontFamily=Recursive;fontSize=14;shadow=1;shadowColor=#000000;shadowOffsetX=4;shadowOffsetY=4;shadowBlur=0;shadowOpacity=6;labelWidth=120;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DRecursive;" vertex="1">
<mxGeometry height="17" width="465" x="10" y="250" as="geometry"/>
</mxCell>
</UserObject>
<UserObject label="Cliente(<u>Id_cliente</u>)" mermaidId="n:Autor" mermaidBaseStyle="html=1;whiteSpace=wrap;strokeWidth=2;fillColor=none;strokeColor=none;fontColor=default;fontFamily=Recursive;fontSize=14;shadow=1;shadowColor=#000000;shadowOffsetX=4;shadowOffsetY=4;shadowBlur=0;shadowOpacity=6;" mermaidBaseValue="Autor (Id_Autor, id_libro)" id="LFypNAhggcB2WLTjAA__-4">
<mxCell parent="LFypNAhggcB2WLTjAA__-1" style="html=1;whiteSpace=wrap;strokeWidth=2;fillColor=none;strokeColor=none;fontColor=default;fontFamily=Recursive;fontSize=14;shadow=1;shadowColor=#000000;shadowOffsetX=4;shadowOffsetY=4;shadowBlur=0;shadowOpacity=6;labelWidth=120;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DRecursive;" vertex="1">
<mxGeometry height="17" width="152" x="100" y="170" as="geometry"/>
</mxCell>
</UserObject>
<UserObject label="" mermaidId="e:Libro->Socio#0" mermaidBaseStyle="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;exitX=0.5;exitY=1;entryX=0.5;entryY=0;strokeWidth=2;targetPerimeterSpacing=4;" mermaidBaseValue="" id="LFypNAhggcB2WLTjAA__-5">
<mxCell edge="1" parent="LFypNAhggcB2WLTjAA__-1" source="LFypNAhggcB2WLTjAA__-3" style="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;strokeWidth=2;targetPerimeterSpacing=4;exitX=0.693;exitY=-0.025;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0.282;entryY=0.667;entryDx=0;entryDy=0;entryPerimeter=0;" target="LFypNAhggcB2WLTjAA__-2">
<mxGeometry relative="1" x="-0.0384" as="geometry">
<Array as="points">
<mxPoint x="332.2" y="160"/>
<mxPoint x="190.1" y="160"/>
</Array>
<mxPoint x="330" y="220" as="sourcePoint"/>
<mxPoint x="420" y="180" as="targetPoint"/>
</mxGeometry>
</mxCell>
</UserObject>
<UserObject label="" mermaidId="e:Autor->Libro#0" mermaidBaseStyle="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;exitX=0.5;exitY=0.99;entryX=0.5;entryY=0;strokeWidth=2;targetPerimeterSpacing=4;" mermaidBaseValue="" id="LFypNAhggcB2WLTjAA__-6">
<mxCell edge="1" parent="LFypNAhggcB2WLTjAA__-1" source="LFypNAhggcB2WLTjAA__-2" style="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;strokeWidth=2;targetPerimeterSpacing=4;exitX=0.651;exitY=0.01;exitDx=0;exitDy=0;exitPerimeter=0;" target="LFypNAhggcB2WLTjAA__-4">
<mxGeometry relative="1" x="0.3548" as="geometry">
<Array as="points">
<mxPoint x="393.1" y="80"/>
<mxPoint x="80" y="80"/>
<mxPoint x="80" y="150"/>
<mxPoint x="176" y="150"/>
</Array>
<mxPoint x="420.78" y="163.05200000000002" as="sourcePoint"/>
<mxPoint x="80" y="170" as="targetPoint"/>
</mxGeometry>
</mxCell>
</UserObject>
<mxCell id="LFypNAhggcB2WLTjAA__-9" parent="LFypNAhggcB2WLTjAA__-1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="Matias Romero 3A" vertex="1">
<mxGeometry height="30" width="110" x="414" y="60" as="geometry"/>
</mxCell>
<mxCell id="LFypNAhggcB2WLTjAA__-10" edge="1" parent="LFypNAhggcB2WLTjAA__-1" style="endArrow=none;html=1;rounded=0;defaultLabelBackgroundColor=gap;entryX=0.907;entryY=0.977;entryDx=0;entryDy=0;entryPerimeter=0;" target="LFypNAhggcB2WLTjAA__-11" value="">
<mxGeometry height="50" relative="1" width="50" as="geometry">
<mxPoint x="170" y="227" as="sourcePoint"/>
<mxPoint x="220" y="227" as="targetPoint"/>
</mxGeometry>
</mxCell>
<UserObject label="Mesero(Id_mesero)" mermaidId="n:Autor" mermaidBaseStyle="html=1;whiteSpace=wrap;strokeWidth=2;fillColor=none;strokeColor=none;fontColor=default;fontFamily=Recursive;fontSize=14;shadow=1;shadowColor=#000000;shadowOffsetX=4;shadowOffsetY=4;shadowBlur=0;shadowOpacity=6;" mermaidBaseValue="Autor (Id_Autor, id_libro)" id="LFypNAhggcB2WLTjAA__-11">
<mxCell parent="LFypNAhggcB2WLTjAA__-1" style="html=1;whiteSpace=wrap;strokeWidth=2;fillColor=none;strokeColor=none;fontColor=default;fontFamily=Recursive;fontSize=14;shadow=1;shadowColor=#000000;shadowOffsetX=4;shadowOffsetY=4;shadowBlur=0;shadowOpacity=6;labelWidth=120;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DRecursive;" vertex="1">
<mxGeometry height="17" width="152" x="100" y="210" as="geometry"/>
</mxCell>
</UserObject>
<UserObject label="" mermaidId="e:Autor->Libro#0" mermaidBaseStyle="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;exitX=0.5;exitY=0.99;entryX=0.5;entryY=0;strokeWidth=2;targetPerimeterSpacing=4;" mermaidBaseValue="" id="LFypNAhggcB2WLTjAA__-16">
<mxCell edge="1" parent="LFypNAhggcB2WLTjAA__-1" source="LFypNAhggcB2WLTjAA__-2" style="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;strokeWidth=2;targetPerimeterSpacing=4;exitX=0.75;exitY=0;exitDx=0;exitDy=0;entryX=0.709;entryY=0.093;entryDx=0;entryDy=0;entryPerimeter=0;" target="LFypNAhggcB2WLTjAA__-11">
<mxGeometry relative="1" x="-0.373" as="geometry">
<Array as="points">
<mxPoint x="447.5" y="100"/>
<mxPoint x="530" y="100"/>
<mxPoint x="530" y="190"/>
<mxPoint x="207.8" y="190"/>
</Array>
<mxPoint x="953" y="240" as="sourcePoint"/>
<mxPoint x="736" y="296" as="targetPoint"/>
</mxGeometry>
</mxCell>
</UserObject>
<UserObject label="Categoria(<u>Id_categoria</u>,id_plato)" mermaidId="n:Autor" mermaidBaseStyle="html=1;whiteSpace=wrap;strokeWidth=2;fillColor=none;strokeColor=none;fontColor=default;fontFamily=Recursive;fontSize=14;shadow=1;shadowColor=#000000;shadowOffsetX=4;shadowOffsetY=4;shadowBlur=0;shadowOpacity=6;" mermaidBaseValue="Autor (Id_Autor, id_libro)" id="LFypNAhggcB2WLTjAA__-12">
<mxCell parent="1" style="html=1;whiteSpace=wrap;strokeWidth=2;fillColor=none;strokeColor=none;fontColor=default;fontFamily=Recursive;fontSize=14;shadow=1;shadowColor=#000000;shadowOffsetX=4;shadowOffsetY=4;shadowBlur=0;shadowOpacity=6;labelWidth=120;fontSource=https%3A%2F%2Ffonts.googleapis.com%2Fcss%3Ffamily%3DRecursive;" vertex="1">
<mxGeometry height="17" width="240" x="100" y="280" as="geometry"/>
</mxCell>
</UserObject>
<UserObject label="" mermaidId="e:Autor->Libro#0" mermaidBaseStyle="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;exitX=0.5;exitY=0.99;entryX=0.5;entryY=0;strokeWidth=2;targetPerimeterSpacing=4;" mermaidBaseValue="" id="LFypNAhggcB2WLTjAA__-19">
<mxCell edge="1" parent="1" source="LFypNAhggcB2WLTjAA__-12" style="edgeStyle=orthogonalEdgeStyle;rounded=1;curved=0;startArrow=none;endArrow=block;endSize=8;strokeColor=default;fillColor=none;jumpStyle=arc;jumpSize=12;strokeWidth=2;targetPerimeterSpacing=4;exitX=0.821;exitY=1.139;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0.358;entryY=-0.071;entryDx=0;entryDy=0;entryPerimeter=0;" target="LFypNAhggcB2WLTjAA__-3">
<mxGeometry relative="1" x="-0.1966" as="geometry">
<Array as="points">
<mxPoint x="297" y="320"/>
<mxPoint x="60" y="320"/>
<mxPoint x="60" y="230"/>
<mxPoint x="176.5" y="230"/>
</Array>
<mxPoint x="573" y="370" as="sourcePoint"/>
<mxPoint x="356" y="426" as="targetPoint"/>
</mxGeometry>
</mxCell>
</UserObject>
</root>
</mxGraphModel>
</diagram>
</mxfile>
