---
layout: page
title: Data Management
permalink: /archival/
---

### Data Provision

To get your research data archived, you need to provide:

* primary research data
* description of the data (metadata) according to ISO 24622-1 (CMDI)
* information on the availability of the data for the public, moratoria, etc.
* a data depositing agreement (only for data providers external to the University of Tübingen)

### Tool Support

* To help package your research data and to support its description, please use
  [**Jack The SIPper**](http://shannon.sfs.uni-tuebingen.de:4411/ "Jack The SIper").

* CLARIN-D provides [DMPTY](https://www.clarin-d.net/en/preparation/data-management-plan "DMPTY"), a data management planner.

### Recommended Formats

<h2>Recommended Formats</h2>
<p>For depositing research data with the Tübingen Archive of Language Resources (TALAR) the following data formats are recommended. In the case of special requirements not addressed by the following recommendations, researchers should contact the archivists at <a class="u-email" href="mailto:clarin-repository@sfs.uni-tuebingen.de">clarin-repository@sfs.uni-tuebingen.de</a>.</p>
<br>
<h3>Textual Resources</h3>
<!-- TABLE FORMATS START -->
<table>
<tr>
<th>Type</th>
<th>Data Format</th>
<th>Recommended File Extension</th>
<th>Recommended MIME Type</th>
<th>Comment</th>
</tr>

<tr>
<td>Text</td>
<td>TXT</td>
<td>.txt</td>
<td>text/plain</td>
<td>recommended</td>
</tr>
<tr>
<td>TEI Documents</td>
<td>XML</td>
<td>.xml</td>
<td>application/xml</td>
<td>recommended</td>
</tr>
<tr>
<td>Document</td>
<td>PDF/A</td>
<td>.pdf</td>
<td>application/pdf</td>
<td>recommended</td>
</tr>
</table>
<h3>Specialised Linguistic Resources</h3>
<table>
<tr>
<th>Type</th>
<th>Data Format</th>
<th>Recommended File Extension</th>
<th>Recommended MIME Type</th>
<th>Comment</th>
</tr>
<tr>
<td>Treebanks</td>
<td>ConLL</td>
<td>.csv, .txt</td>
<td>text/plain</td>
<td>recommended</td>
</tr>
<tr>
<td>Treebanks</td>
<td>negra</td>
<td>.csv, .txt</td>
<td>text/plain</td>
<td>recommended</td>
</tr>
<tr>
<td>TCF</td>
<td>XML</td>
<td>.tcf</td>
<td>application/xml+tcf</td>
<td>recommended</td>
</tr>
<tr>
<td>E-Run Experiment File</td>
<td>E-Run</td>
<td>.ebs2</td>
<td>application/octet-stream</td>
<td>accepted</td>
</tr>
<tr>
<td>E-Merge Experiment File</td>
<td>E-Merge</td>
<td>.emrg2</td>
<td>application/x-ole-storage</td>
<td>accepted</td>
</tr>
<tr>
<td>E-Studio Experimental File</td>
<td>E-Studio</td>
<td>.es2</td>
<td>text/plain</td>
<td>accepted</td>
</tr>
<tr>
<td>Feature Structures</td>
<td>HPSG</td>
<td>.skip</td>
<td>text/plain</td>
<td>legacy, now recommended: TEI</td>
</tr>
<tr>
<td>Feature Structures</td>
<td>TDL</td>
<td>.tdl</td>
<td>text/plain</td>
<td>legacy, now recommended: TEI</td>
</tr>
<tr>
<td>Diverse</td>
<td>tusnelda</td>
<td>.sgml</td>
<td>text/sgml</td>
<td>legacy, now recommended: TEI</td>
</tr>
</table>
<h3>Archive Packages</h3>
<p>The content of these packaging formats should follow the TALAR recommendations.</p>
<table>
<tr>
<th>Type</th>
<th>Data Format</th>
<th>Recommended File Extension</th>
<th>Recommended MIME Type</th>
<th>Comment</th>
</tr>
<tr>
<td></td>
<td>GNU zip</td>
<td>.gz</td>
<td>application/gzip, application/x-gzip</td>
<td>recommended</td>
</tr>
<tr>
<td></td>
<td>RAR</td>
<td>.rar</td>
<td>application/x-rar</td>
<td>recommended</td>
</tr>
<tr>
<td></td>
<td>TAR-GZ</td>
<td>.tgz</td>
<td>application/gzip</td>
<td>recommended</td>
</tr>
<tr>
<td></td>
<td>TAR</td>
<td>.tar</td>
<td>application/x-tar</td>
<td>recommended</td>
</tr>
<tr>
<td></td>
<td>Zip</td>
<td>.zip</td>
<td>application/zip</td>
<td>recommended</td>
</tr>
</table>
<h3>Statistics Files and Program Code</h3>
<table>
<tr>
<th>Type</th>
<th>Data Format</th>
<th>Recommended File Extension</th>
<th>Recommended MIME Type</th>
<th>Comment</th>
</tr>
<tr>
<td>Program Code</td>
<td>R</td>
<td>.r / .R</td>
<td>text/plain, text/x-matlab</td>
<td>recommended</td>
</tr>
<tr>
<td>SPSS Statistics</td>
<td>SPSS</td>
<td>.sav</td>
<td>application/spss-sav</td>
<td>recommended</td>
</tr>
<tr>
<td>SPSS Statistics</td>
<td>SPSS</td>
<td>.spss</td>
<td>application/spss</td>
<td>recommended</td>
</tr>
<tr>
<td>SPSS Statistics</td>
<td>SPSS</td>
<td>.spv</td>
<td>application/x-spss-spv</td>
<td>recommended</td>
</tr>
<tr>
<td>Program Code</td>
<td>Lisp</td>
<td>.lsp</td>
<td>text/plain</td>
<td>recommended</td>
</tr>
<tr>
<td>Tables</td>
<td>CSV</td>
<td>.csv</td>
<td>text/plain</td>
<td>recommended</td>
</tr>
<tr>
<td>Tab Separated Data File</td>
<td>TAB</td>
<td>.tab</td>
<td>text/plain</td>
<td>recommended</td>
</tr>
<tr>
<td>Script</td>
<td>Perl Script</td>
<td>.pl</td>
<td>application/x-perl</td>
<td>recommended</td>
</tr>
</table>
<h3>Media Resources</h3>
<table>
<tr>
<th>Type</th>
<th>Data Format</th>
<th>Recommended File Extension</th>
<th>Recommended MIME Type</th>
<th>Comment</th>
</tr>
<tr>
<td>Image</td>
<td>BMP</td>
<td>.bmp</td>
<td>image/bmp</td>
<td>recommended</td>
</tr>
<tr>
<td>Image</td>
<td>JPEG</td>
<td>.jpg</td>
<td>image/jpep</td>
<td>recommended</td>
</tr>
<tr>
<td>Image</td>
<td>PNG</td>
<td>.png</td>
<td>image/png</td>
<td>recommended</td>
</tr>
<tr>
<td>Image</td>
<td>TIFF</td>
<td>.tiff</td>
<td>image/tiff</td>
<td>recommended</td>
</tr>
<tr>
<td>Image</td>
<td>GIF</td>
<td>.gif</td>
<td>image/gif</td>
<td>recommended</td>
</tr>
<tr>
<td>Vector Graphic</td>
<td>SVG</td>
<td>.svg</td>
<td>image/svg+xml</td>
<td>recommended</td>
</tr>
<tr>
<td>Audio</td>
<td>WAVE</td>
<td>.wav</td>
<td>audio/wav</td>
<td>recommended</td>
</tr>
<tr>
<td>Video</td>
<td>M4V</td>
<td>.m4v</td>
<td>application/octet-stream</td>
<td>recommended</td>
</tr>
<tr>
<td>Document</td>
<td>PDF/A</td>
<td>.pdf</td>
<td>application/pdf</td>
<td>recommended</td>
</tr>
<tr>
<td>Biosemi EEG file</td>
<td>Biosemi</td>
<td>.bdf</td>
<td>biosig/bdf</td>
<td>accepted</td>
</tr>
</table>
<h3>Other Resources</h3>
<table>
<tr>
<th >Type</th>
<th>Data Format</th>
<th>Recommended File Extension</th>
<th>Recommended MIME Type</th>
<th>Comment</th>
</tr>
<tr>
<td>Stylesheet</td>
<td>CSS</td>
<td>.css</td>
<td>text/plain</td>
<td>recommended</td>
</tr>
<tr>
<td>Document Type Definition</td>
<td>DTD</td>
<td>.dtd</td>
<td>application/xml-dtd</td>
<td>legacy, now XSD</td>
</tr>
<tr>
<td>Extensible Markup Language</td>
<td>XML</td>
<td>.xml</td>
<td>application/xml, text/xml</td>
<td>recommended</td>
</tr>
<tr>
<td>Xschema</td>
<td>XSD</td>
<td>.xsd</td>
<td>application/xml, text/xml</td>
<td>recommended</td>
</tr>
<tr>
<td>Text</td>
<td>HTML</td>
<td>.html</td>
<td>text/html</td>
<td>recommended</td>
</tr>
<tr>
<td>Text</td>
<td>HTML</td>
<td>.xhtml</td>
<td>text/html</td>
<td>recommended</td>
</tr>
<tr>
<td>Database File</td>
<td>SQLite</td>
<td>.sqlite</td>
<td>application/x-sqlite3</td>
<td>recommended</td>
</tr>
<tr>
<td>Stylesheet</td>
<td>XML</td>
<td>.xsl</td>
<td>application/xslt+xml</td>
<td>recommended</td>
</tr>
<tr>
<td>Metadata in CMDI</td>
<td>XML</td>
<td>.xml</td>
<td>application/xml+cmdi</td>
<td>recommended</td>
</tr>
<tr>
<td>Bibliography Document</td>
<td>BibTeX</td>
<td>.bib</td>
<td>text/plain</td>
<td>recommended</td>
</tr>
<tr>
<td>Jupyter Notebook</td>
<td>Jupyter Notebook</td>
<td>.ipynb</td>
<td>text/plain</td>
<td>accepted</td>
</tr>
<tr>
<td>Presentation</td>
<td>PowerPoint Presentation</td>
<td>.pptx</td>
<td>application/vnd.openxmlformats-officedocument.presentationml.presentation</td>
<td>accepted</td>
</tr>

</table>
<h3>Legacy Data</h3>
<table>
<tr>
<th>Type</th>
<th>Data Format</th>
<th>Recommended File Extension</th>
<th>Recommended MIME Type</th>
<th>Comment</th>
</tr>
<tr>
<td>Text Document</td>
<td>DOC</td>
<td>.doc</td>
<td>application/msword</td>
<td>not accepted for new data, tolerated for legacy data for the moment</td>
</tr>
<tr>
<td>Text Document</td>
<td>DOCX</td>
<td>.docx</td>
<td>application/vnd.openxmlformats-officedocument.wordprocessingml.document</td>
<td>not accepted for new data, tolerated for legacy data for the moment</td>
</tr>
<tr>
<td>Text Document</td>
<td>RTF</td>
<td>.rtf</td>
<td>text/plain</td>
<td>not accepted for new data, tolerated for legacy data for the moment</td>
</tr>
<tr>
<td>Text Document </td>
<td>OpenDocument Text Document </td>
<td>.odt </td>
<td>application/vnd.oasis.opendocument.text </td>
<td>accepted if containing formulas and other active components </td>
</tr>
<tr>
<td>Text Document</td>
<td>Microsoft Access</td>
<td>.mdb</td>
<td>application/vnd.ms-access</td>
<td>not accepted for new data, tolerated for legacy data for the moment</td>
</tr>
<tr>
<td>Database File</td>
<td>Microsoft Access</td>
<td>.accdb</td>
<td>text/plain</td>
<td>not accepted for new data, tolerated for legacy data for the moment</td>
</tr>
<tr>
<td>Table</td>
<td>OpenDocument Spreadsheet</td>
<td>.ods</td>
<td>application/vnd.oasis.opendocument.spreadsheet</td>
<td>accepted if containing formulas and other active components</td>
</tr>
<tr>
<td>Table</td>
<td>Excel Spreadsheet</td>
<td>.xls</td>
<td>application/vnd.ms-excel</td>
<td>accepted if containing formulas and other active components</td>
</tr>
<tr>
<td>Table</td>
<td>Excel Spreadsheet</td>
<td>.xlsx </td>
<td>application/vnd.openxmlformats-officedocument.spreadsheetml.sheet</td>
<td>accepted if containing formulas and other active components</td>
</tr>
<tr>
<td>Presentation</td>
<td>PowerPoint Presentation</td>
<td>.ppt</td>
<td>application/vnd.ms-powerpoint</td>
<td>not accepted for new data, tolerated for legacy data for the moment</td>
</tr>
<tr>
<td>Presentation</td>
<td>PowerPoint Presentation</td>
<td>.pptm</td>
<td>application/vnd.ms-powerpoint.presentation.macroEnabled.12</td>
<td>not accepted for new data, tolerated for legacy data for the moment</td>
</tr>
<tr>
<td>Presentation</td>
<td>Mac OS X-Paket-Format</td>
<td>.key</td>
<td>application/vnd.apple.keynote</td>
<td>not accepted for new data, tolerated for legacy data for the moment</td>
</tr>
<tr>
<td>Variable Property Mapping</td>
<td> </td>
<td>.vpm</td>
<td>text/plain</td>
<td>not accepted for new data, tolerated for legacy data for the moment</td>
</tr>
</table>
<!-- TABLE FORMATS END -->
<p>Status of 2020-02-21</p>
