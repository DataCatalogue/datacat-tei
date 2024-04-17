## Table of Equivalence between the DataCatalogue SegmOnto Classes and the TEI

[😺 **Disclaimer**] The TEI elements are displayed **context-free** in this table. For example, ```<head>``` appears several times, but its parent element will be different depending on the context (```<figure>``` or ```<div>``` for example).  


| Class Name                        | TEI                                                           |
|:----------------------------------|:--------------------------------------------------------------|
| DigitizationArtefactZone          | ```<repository>```                                            |
| GraphicZone                       | ```<figure>```                                                |
| GraphicZone:Decoration            | ```<figure type="decoration">```                              |
| GraphicZone:FigDesc               | ```<figDesc>```                                               |
| GraphicZone:Head                  | ```<head>```                                                  |
| MainZone:Entry                    | ```<catalogueItem>```                                         |
| MainZone:Form                     | ```<div type="form">```                                       |
| MainZone:Head                     | ```<head>```                                                  |
| MainZone:List                     | ```<list>```                                                  |
| MainZone:Other                    | ```<div type="other">```                                      |
| MainZone:P                        | ```<p>```                                                     |
| MainZone:P@CatalogueDesc          | ```<catalogueDesc>```                                         |
| MainZone:Signature                | ```<signed>```                                                |
| MarginTextZone:ManuscriptAddendum | ```<div type="handwritten">```                                |
| MarginTextZone:Notes              | ```<note>```                                                  |
| NumberingZone                     | ```<pb n="">```                                               |
| PageTitleZone                     | ```<div type="titlepage">``` / ```<titlePage>```              |
| PageTitleZone:Index               | ```<div type="toc">```                                        |
| QuireMarkZone                     | ```<fw type="quiremark">```                                   |
| RunningTitleZone                  | ```<fw type="header">```                                      |
| StampZone                         | ```<figure type="stamp">``` / ```<stamp>```                   |
| StampZone:Sticker                 | ```<figure type="sticker">``` / ```<stamp type="sticker>```   |
| TableZone                         | ```<figure type="table">``` / ```<table>```                   |