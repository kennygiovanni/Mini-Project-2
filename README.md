[minpro2.drawio](https://github.com/user-attachments/files/22582842/minpro2.drawio)Penjelasan baris code:

baris 1-2 : tampilkan salam pembuka
baris 4-6 : Dictionary berisi username (password, role)
baris 9 : List untuk menyimpan hasil pertandingan
baris 11-32 : Function untuk login
baris 34-58 : Function untuk menambah data pertandingan
baris 60-71 : Function untuk melihat hasil pertandingan
baris 73-88 : Function untuk menghapus hasil pertandingan
baris 90-133 : Function untuk keluar dari program dan kembali ke menu
baris 135-156 : Function untuk menu sebagai admin
baris 158-172 : Function untuk menu sebagai viewer
baris 174-178 : Memanggil fungsi login saat membuka menu agar sesuai dengan role penggunanya

Flowchart: 

[<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/140.0.0.0 Safari/537.36 Edg/140.0.0.0" version="28.2.1">
  <diagram name="Page-1" id="AV1i5gVp13iIYDWPMeXJ">
    <mxGraphModel grid="1" page="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" pageScale="1" pageWidth="850" pageHeight="1100" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="X8HX99xs4B6dVfBDjnRm-3" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-1" target="X8HX99xs4B6dVfBDjnRm-2">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-1" value="Mulai" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="365" width="120" height="80" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-5" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-2">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="425" y="200" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-2" value="Cek role user" style="rounded=1;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="365" y="110" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-14" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" target="X8HX99xs4B6dVfBDjnRm-13">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="425" y="260" as="sourcePoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-11" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="425" y="350" as="sourcePoint" />
            <mxPoint x="425" y="380" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-22" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-13" target="X8HX99xs4B6dVfBDjnRm-21">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-13" value="Cek data login" style="whiteSpace=wrap;html=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="365" y="200" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-24" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-21" target="X8HX99xs4B6dVfBDjnRm-23">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-21" value="Masukkan nama dan password" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="365" y="290" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-25" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0.75;entryDx=0;entryDy=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-23" target="X8HX99xs4B6dVfBDjnRm-21">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="526.1538461538462" y="331.53846153846155" as="targetPoint" />
            <mxPoint x="520" y="420" as="sourcePoint" />
            <Array as="points">
              <mxPoint x="520" y="420" />
              <mxPoint x="520" y="332" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-27" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-23" target="X8HX99xs4B6dVfBDjnRm-26">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-23" value="Apakah login berhasil?" style="rhombus;whiteSpace=wrap;html=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="385" y="380" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-29" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-26" target="X8HX99xs4B6dVfBDjnRm-28">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-86" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0;exitDx=0;exitDy=0;entryX=0.5;entryY=1;entryDx=0;entryDy=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-26" target="X8HX99xs4B6dVfBDjnRm-32">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="405" y="480" />
              <mxPoint x="300" y="480" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-26" value="Admin?" style="rhombus;whiteSpace=wrap;html=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="385" y="490" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-31" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-28" target="X8HX99xs4B6dVfBDjnRm-30">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-28" value="Menu admin" style="whiteSpace=wrap;html=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="240" y="500" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-37" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-30" target="X8HX99xs4B6dVfBDjnRm-36">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-42" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=1;exitDx=0;exitDy=0;entryX=0.587;entryY=0.047;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-30">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="230.44000000000005" y="702.8199999999999" as="targetPoint" />
            <Array as="points">
              <mxPoint x="230" y="660" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-47" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-30">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="360" y="700" as="targetPoint" />
            <Array as="points">
              <mxPoint x="360" y="660" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-98" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-30" target="X8HX99xs4B6dVfBDjnRm-75">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-30" value="Pilihan admin?" style="rhombus;whiteSpace=wrap;html=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="260" y="600" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-87" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-32" target="X8HX99xs4B6dVfBDjnRm-34">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-32" value="Menu viewer" style="whiteSpace=wrap;html=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="240" y="390" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-103" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-34" target="X8HX99xs4B6dVfBDjnRm-102">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-105" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-34" target="X8HX99xs4B6dVfBDjnRm-100">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-34" value="Lihat hasil pertandingan" style="rhombus;whiteSpace=wrap;html=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="120" y="380" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-40" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-36" target="X8HX99xs4B6dVfBDjnRm-39">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-36" value="Input data pertandingan" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="90" y="610" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-38" value="Tambah&amp;nbsp;" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="210" y="610" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-43" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-39" target="X8HX99xs4B6dVfBDjnRm-28">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint y="530" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-39" value="Data tersimpan" style="whiteSpace=wrap;html=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="-60" y="610" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-44" value="Lihat" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="180" y="670" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-48" value="Hapus" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="350" y="660" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-99" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-50" target="X8HX99xs4B6dVfBDjnRm-52">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-50" value="Tampilkan daftar pertandingan" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" vertex="1" parent="1">
          <mxGeometry x="300" y="700" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-55" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-52" target="X8HX99xs4B6dVfBDjnRm-54">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-52" value="Masukkan nomor pertandingan yang dihapus" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" vertex="1" parent="1">
          <mxGeometry x="300" y="810" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-57" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-54" target="X8HX99xs4B6dVfBDjnRm-56">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-90" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-54" target="X8HX99xs4B6dVfBDjnRm-50">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="460" y="830" as="targetPoint" />
            <Array as="points">
              <mxPoint x="440" y="950" />
              <mxPoint x="440" y="730" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-54" value="Nomor valid?" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="320" y="910" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-59" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-56" target="X8HX99xs4B6dVfBDjnRm-58">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-56" value="Hapus pertandingan dari daftar" style="whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="160" y="920" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-58" value="Tampilkan konfirmasi penghapusan" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" vertex="1" parent="1">
          <mxGeometry x="10" y="920" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-62" value="ya" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="270" y="920" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-74" value="Keluar" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="400" y="620" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-79" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-75" target="X8HX99xs4B6dVfBDjnRm-78">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-94" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0;exitDx=0;exitDy=0;entryX=1;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-75" target="X8HX99xs4B6dVfBDjnRm-30">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-75" value="kembali ke menu" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="520" y="600" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-77" value="ya" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="390" y="590" width="115" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-83" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;entryX=0.958;entryY=0.387;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-78" target="X8HX99xs4B6dVfBDjnRm-21">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="580" y="300" as="targetPoint" />
            <Array as="points">
              <mxPoint x="690" y="313" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-120" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-78" target="X8HX99xs4B6dVfBDjnRm-118">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-78" value="Keluar dari program" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="650" y="600" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-80" value="tidak" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="600" y="610" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-84" value="tidak" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="640" y="440" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-91" value="tidak" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="390" y="920" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-92" value="Output daftar hasil pertandingan" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" vertex="1" parent="1">
          <mxGeometry x="170" y="700" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-95" value="ya" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="385" y="450" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-96" value="tidak" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="450" y="390" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-107" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-100" target="X8HX99xs4B6dVfBDjnRm-32">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-111" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-100" target="X8HX99xs4B6dVfBDjnRm-110">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-100" value="keluar?&amp;nbsp;" style="rhombus;whiteSpace=wrap;html=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="120" y="260" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-102" value="Tampilkan daftar hasil pertandingan" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="-50" y="390" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-108" value="Ya" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="70" y="390" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-109" value="tidak" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="190" y="270" width="115" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-112" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;entryX=0.042;entryY=0.333;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-110" target="X8HX99xs4B6dVfBDjnRm-21">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="340" y="260" as="targetPoint" />
            <Array as="points">
              <mxPoint y="240" />
              <mxPoint x="340" y="240" />
              <mxPoint x="340" y="310" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-119" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=0.5;entryY=1;entryDx=0;entryDy=0;" edge="1" parent="1" source="X8HX99xs4B6dVfBDjnRm-110" target="X8HX99xs4B6dVfBDjnRm-118">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="-100" y="1071.0000610351562" as="targetPoint" />
            <Array as="points">
              <mxPoint x="-80" y="300" />
              <mxPoint x="-80" y="1030" />
              <mxPoint x="560" y="1030" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-110" value="keluar?" style="rhombus;whiteSpace=wrap;html=1;rounded=1;" vertex="1" parent="1">
          <mxGeometry x="-40" y="260" width="80" height="80" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-113" value="tidak" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="130" y="210" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-114" value="tidak" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="330" y="460" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-115" value="ya" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="350" y="500" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-116" value="ya" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="50" y="270" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-117" value="tidak" style="text;strokeColor=none;align=center;fillColor=none;html=1;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="125" y="350" width="115" height="30" as="geometry" />
        </mxCell>
        <mxCell id="X8HX99xs4B6dVfBDjnRm-118" value="Selesai" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="500" y="740" width="120" height="80" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
Uploading minpro2.drawio…]()
