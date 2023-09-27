# Banco-de-Dados
Repositório criado para a disciplina de banco de dados na faculdade Newton Paiva.
## Projeto conceitual de banco de dados para o aplicativo ZÉ DELIVERY
Felipe Araújo Costa

RA-12121137


[Uploading ZE<mxfile host="app.diagrams.net" modified="2023-09-27T15:33:54.300Z" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/117.0.0.0 Safari/537.36" etag="ZoKtNnkHCo4LfQWbp9rQ" version="21.8.0" type="device">
  <diagram name="Página-1" id="UR4jZJC76uRAmZpg9dqt">
    <mxGraphModel dx="1588" dy="928" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="dq2QHWxk1mMoR289qEDF-1" value="ITEM_PEDIDO" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="50" y="100" width="180" height="150" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-2" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-1">
          <mxGeometry y="30" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-3" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-2">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-4" value="COD_ITEM" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-2">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-5" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-1">
          <mxGeometry y="60" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-6" value="FK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-5">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-7" value="COD_PEDIDO" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-5">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-8" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-1">
          <mxGeometry y="90" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-9" value="FK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-8">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-10" value="COD_PRODUTO" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-8">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-11" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-1">
          <mxGeometry y="120" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-12" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-11">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-13" value="QTD_ITEM_PEDIDO(int)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-11">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-14" value="PEDIDOS" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="298" y="90" width="230" height="180" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-15" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-14">
          <mxGeometry y="30" width="230" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-16" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-15">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-17" value="COD_PEDIDO" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-15">
          <mxGeometry x="30" width="200" height="30" as="geometry">
            <mxRectangle width="200" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-18" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-14">
          <mxGeometry y="60" width="230" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-19" value="FK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-18">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-20" value="COD_CLIENTE" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-18">
          <mxGeometry x="30" width="200" height="30" as="geometry">
            <mxRectangle width="200" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-21" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-14">
          <mxGeometry y="90" width="230" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-22" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-21">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-23" value="DATA_PEDIDO(datetime)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-21">
          <mxGeometry x="30" width="200" height="30" as="geometry">
            <mxRectangle width="200" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-24" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-14">
          <mxGeometry y="120" width="230" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-25" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-24">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-26" value="COD_SITUAÇAO_PEDIDO(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-24">
          <mxGeometry x="30" width="200" height="30" as="geometry">
            <mxRectangle width="200" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-53" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-14">
          <mxGeometry y="150" width="230" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-54" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-53">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-55" value="VLR_PEDIDO(double)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-53">
          <mxGeometry x="30" width="200" height="30" as="geometry">
            <mxRectangle width="200" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-57" value="CLIENTES" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="670" y="90" width="180" height="270" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-58" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-57">
          <mxGeometry y="30" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-59" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-58">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-60" value="COD_CLIENTE" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-58">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-61" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-57">
          <mxGeometry y="60" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-62" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-61">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-63" value="LOGIN(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-61">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-64" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-57">
          <mxGeometry y="90" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-65" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-64">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-66" value="SENHA(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-64">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-67" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-57">
          <mxGeometry y="120" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-68" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-67">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-69" value="NOME(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-67">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-70" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-57">
          <mxGeometry y="150" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-71" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-70">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-72" value="CPF(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-70">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-73" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-57">
          <mxGeometry y="180" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-74" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-73">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-75" value="EMAIL(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-73">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-76" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-57">
          <mxGeometry y="210" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-77" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-76">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-78" value="ENDEREÇO(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-76">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-79" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-57">
          <mxGeometry y="240" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-80" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-79">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-81" value="TELEFONE(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-79">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-82" value="FORNECEDOR" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="930" y="120" width="180" height="150" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-83" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-82">
          <mxGeometry y="30" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-84" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-83">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-85" value="COD_FORNECEDOR" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-83">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-86" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-82">
          <mxGeometry y="60" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-87" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-86">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-88" value="NOME(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-86">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-89" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-82">
          <mxGeometry y="90" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-90" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-89">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-91" value="TELEFONE(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-89">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-92" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-82">
          <mxGeometry y="120" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-93" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-92">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-94" value="ENDEREÇO(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-92">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-95" value="ESTOQUE" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="950" y="380" width="180" height="150" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-96" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-95">
          <mxGeometry y="30" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-97" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-96">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-98" value="COD_ESTOQUE" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-96">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-99" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-95">
          <mxGeometry y="60" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-100" value="FK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-99">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-101" value="COD_FORNECEDOR" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-99">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-102" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-95">
          <mxGeometry y="90" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-103" value="FK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-102">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-104" value="COD_PRODUTO" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-102">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-105" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-95">
          <mxGeometry y="120" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-106" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-105">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-107" value="QTD_DISPONIVEL(int)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-105">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-108" value="RELATORIO_VENDA" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="700" y="560" width="245" height="180" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-109" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-108">
          <mxGeometry y="30" width="245" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-110" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-109">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-111" value="COD_RELATORIO" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-109">
          <mxGeometry x="30" width="215" height="30" as="geometry">
            <mxRectangle width="215" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-112" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-108">
          <mxGeometry y="60" width="245" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-113" value="FK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-112">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-114" value="COD_LOJA" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-112">
          <mxGeometry x="30" width="215" height="30" as="geometry">
            <mxRectangle width="215" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-115" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-108">
          <mxGeometry y="90" width="245" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-116" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-115">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-117" value="VALOR_VENDA(double)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-115">
          <mxGeometry x="30" width="215" height="30" as="geometry">
            <mxRectangle width="215" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-118" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-108">
          <mxGeometry y="120" width="245" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-119" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-118">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-120" value="DTA_INICIAL_RELATORIO(datetime)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-118">
          <mxGeometry x="30" width="215" height="30" as="geometry">
            <mxRectangle width="215" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-121" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-108">
          <mxGeometry y="150" width="245" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-122" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-121">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-123" value="DTA_FIM_RELATORIO(datetime)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-121">
          <mxGeometry x="30" width="215" height="30" as="geometry">
            <mxRectangle width="215" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-124" value="PRODUTOS" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="338" y="310" width="202" height="150" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-125" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-124">
          <mxGeometry y="30" width="202" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-126" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-125">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-127" value="COD_PRODUTO" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-125">
          <mxGeometry x="30" width="172" height="30" as="geometry">
            <mxRectangle width="172" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-128" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-124">
          <mxGeometry y="60" width="202" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-129" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-128">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-130" value="NOME_PRODUTO(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-128">
          <mxGeometry x="30" width="172" height="30" as="geometry">
            <mxRectangle width="172" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-131" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-124">
          <mxGeometry y="90" width="202" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-132" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-131">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-133" value="VALOR_PRODUTO(double)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-131">
          <mxGeometry x="30" width="172" height="30" as="geometry">
            <mxRectangle width="172" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-134" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-124">
          <mxGeometry y="120" width="202" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-135" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-134">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-136" value="QTD_PRODUTO(int)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-134">
          <mxGeometry x="30" width="172" height="30" as="geometry">
            <mxRectangle width="172" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-137" value="VENDEDORES" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="348" y="605" width="232" height="191.88" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-138" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-137">
          <mxGeometry y="30" width="232" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-139" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-138">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-140" value="COD_VENDEDOR" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-138">
          <mxGeometry x="30" width="202" height="30" as="geometry">
            <mxRectangle width="202" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-141" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-137">
          <mxGeometry y="60" width="232" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-142" value="FK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-141">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-143" value="COD_LOJA" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-141">
          <mxGeometry x="30" width="202" height="30" as="geometry">
            <mxRectangle width="202" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-144" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-137">
          <mxGeometry y="90" width="232" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-145" value="FK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-144">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-146" value="COD_CLIENTE" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-144">
          <mxGeometry x="30" width="202" height="30" as="geometry">
            <mxRectangle width="202" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-147" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-137">
          <mxGeometry y="120" width="232" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-148" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-147">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-149" value="NOME_VENDEDOR(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-147">
          <mxGeometry x="30" width="202" height="30" as="geometry">
            <mxRectangle width="202" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-163" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-137">
          <mxGeometry y="150" width="232" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-164" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-163">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-165" value="TELEFONE_VENDEDOR(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-163">
          <mxGeometry x="30" width="202" height="30" as="geometry">
            <mxRectangle width="202" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-172" value="LOJA" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;" vertex="1" parent="1">
          <mxGeometry x="80" y="400" width="180" height="150" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-173" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-172">
          <mxGeometry y="30" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-174" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-173">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-175" value="COD_LOJA" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-173">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-176" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-172">
          <mxGeometry y="60" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-177" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-176">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-178" value="NOME(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-176">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-179" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-172">
          <mxGeometry y="90" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-180" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-179">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-181" value="ENDEREÇO(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-179">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-182" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-172">
          <mxGeometry y="120" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-183" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-182">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-184" value="TELEFONE(string)" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="dq2QHWxk1mMoR289qEDF-182">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-187" value="" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="dq2QHWxk1mMoR289qEDF-5" target="dq2QHWxk1mMoR289qEDF-15">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="430" y="350" as="sourcePoint" />
            <mxPoint x="530" y="330" as="targetPoint" />
            <Array as="points">
              <mxPoint x="260" y="140" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-188" value="" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="dq2QHWxk1mMoR289qEDF-8" target="dq2QHWxk1mMoR289qEDF-125">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="480" y="380" as="sourcePoint" />
            <mxPoint x="530" y="330" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-189" value="" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="dq2QHWxk1mMoR289qEDF-173" target="dq2QHWxk1mMoR289qEDF-141">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="480" y="620" as="sourcePoint" />
            <mxPoint x="530" y="570" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-190" value="" style="endArrow=none;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" target="dq2QHWxk1mMoR289qEDF-112">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="260" y="450" as="sourcePoint" />
            <mxPoint x="530" y="570" as="targetPoint" />
            <Array as="points">
              <mxPoint x="390" y="560" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-191" value="" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="dq2QHWxk1mMoR289qEDF-125" target="dq2QHWxk1mMoR289qEDF-102">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="680" y="480" as="sourcePoint" />
            <mxPoint x="730" y="430" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-192" value="" style="endArrow=none;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="dq2QHWxk1mMoR289qEDF-144" target="dq2QHWxk1mMoR289qEDF-58">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="640" y="470" as="sourcePoint" />
            <mxPoint x="690" y="420" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-193" value="" style="endArrow=none;html=1;rounded=0;entryX=0.01;entryY=0.233;entryDx=0;entryDy=0;entryPerimeter=0;exitX=0;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="dq2QHWxk1mMoR289qEDF-99" target="dq2QHWxk1mMoR289qEDF-83">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="880" y="400" as="sourcePoint" />
            <mxPoint x="930" y="350" as="targetPoint" />
            <Array as="points">
              <mxPoint x="910" y="300" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="dq2QHWxk1mMoR289qEDF-194" value="" style="endArrow=none;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="dq2QHWxk1mMoR289qEDF-18" target="dq2QHWxk1mMoR289qEDF-58">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="570" y="190" as="sourcePoint" />
            <mxPoint x="620" y="140" as="targetPoint" />
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
 LOGICA 2.0.drawio…]()




