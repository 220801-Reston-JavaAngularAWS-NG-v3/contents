<html xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word"
xmlns:m="http://schemas.microsoft.com/office/2004/12/omml"
xmlns="http://www.w3.org/TR/REC-html40">

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1252">
<meta name=ProgId content=Word.Document>
<meta name=Generator content="Microsoft Word 15">
<meta name=Originator content="Microsoft Word 15">
<link rel=File-List href="6-JS-type-coercion_files/filelist.xml">
<!--[if gte mso 9]><xml>
 <o:DocumentProperties>
  <o:Author>Balaji</o:Author>
  <o:Template>Normal</o:Template>
  <o:LastAuthor>Balaji</o:LastAuthor>
  <o:Revision>42</o:Revision>
  <o:TotalTime>117</o:TotalTime>
  <o:Created>2022-08-18T04:28:00Z</o:Created>
  <o:LastSaved>2022-08-18T06:27:00Z</o:LastSaved>
  <o:Pages>4</o:Pages>
  <o:Words>693</o:Words>
  <o:Characters>3956</o:Characters>
  <o:Lines>32</o:Lines>
  <o:Paragraphs>9</o:Paragraphs>
  <o:CharactersWithSpaces>4640</o:CharactersWithSpaces>
  <o:Version>15.00</o:Version>
 </o:DocumentProperties>
 <o:OfficeDocumentSettings>
  <o:AllowPNG/>
 </o:OfficeDocumentSettings>
</xml><![endif]-->
<link rel=themeData href="6-JS-type-coercion_files/themedata.thmx">
<link rel=colorSchemeMapping
href="6-JS-type-coercion_files/colorschememapping.xml">
<!--[if gte mso 9]><xml>
 <w:WordDocument>
  <w:View>Print</w:View>
  <w:SpellingState>Clean</w:SpellingState>
  <w:GrammarState>Clean</w:GrammarState>
  <w:TrackMoves>false</w:TrackMoves>
  <w:TrackFormatting/>
  <w:ValidateAgainstSchemas/>
  <w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid>
  <w:IgnoreMixedContent>false</w:IgnoreMixedContent>
  <w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText>
  <w:DoNotPromoteQF/>
  <w:LidThemeOther>EN-IN</w:LidThemeOther>
  <w:LidThemeAsian>X-NONE</w:LidThemeAsian>
  <w:LidThemeComplexScript>X-NONE</w:LidThemeComplexScript>
  <w:Compatibility>
   <w:BreakWrappedTables/>
   <w:SplitPgBreakAndParaMark/>
  </w:Compatibility>
  <w:BrowserLevel>MicrosoftInternetExplorer4</w:BrowserLevel>
  <m:mathPr>
   <m:mathFont m:val="Cambria Math"/>
   <m:brkBin m:val="before"/>
   <m:brkBinSub m:val="&#45;-"/>
   <m:smallFrac m:val="off"/>
   <m:dispDef/>
   <m:lMargin m:val="0"/>
   <m:rMargin m:val="0"/>
   <m:defJc m:val="centerGroup"/>
   <m:wrapIndent m:val="1440"/>
   <m:intLim m:val="subSup"/>
   <m:naryLim m:val="undOvr"/>
  </m:mathPr></w:WordDocument>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <w:LatentStyles DefLockedState="false" DefUnhideWhenUsed="false"
  DefSemiHidden="false" DefQFormat="false" DefPriority="99"
  LatentStyleCount="371">
  <w:LsdException Locked="false" Priority="0" QFormat="true" Name="Normal"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 1"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 2"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 3"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 4"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 5"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 6"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 7"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 8"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 9"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 1"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 2"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 3"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 4"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 5"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 6"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 7"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 8"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="header"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footer"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index heading"/>
  <w:LsdException Locked="false" Priority="35" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="caption"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of figures"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope return"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="line number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="page number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of authorities"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="macro"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="toa heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 5"/>
  <w:LsdException Locked="false" Priority="10" QFormat="true" Name="Title"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Closing"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Signature"/>
  <w:LsdException Locked="false" Priority="1" SemiHidden="true"
   UnhideWhenUsed="true" Name="Default Paragraph Font"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Message Header"/>
  <w:LsdException Locked="false" Priority="11" QFormat="true" Name="Subtitle"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Salutation"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Date"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Note Heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Block Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Hyperlink"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="FollowedHyperlink"/>
  <w:LsdException Locked="false" Priority="22" QFormat="true" Name="Strong"/>
  <w:LsdException Locked="false" Priority="20" QFormat="true" Name="Emphasis"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Document Map"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Plain Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="E-mail Signature"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Top of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Bottom of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal (Web)"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Acronym"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Cite"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Code"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Definition"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Keyboard"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Preformatted"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Sample"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Typewriter"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Variable"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Table"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation subject"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="No List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Contemporary"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Elegant"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Professional"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Balloon Text"/>
  <w:LsdException Locked="false" Priority="39" Name="Table Grid"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Theme"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Placeholder Text"/>
  <w:LsdException Locked="false" Priority="1" QFormat="true" Name="No Spacing"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 1"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 1"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Revision"/>
  <w:LsdException Locked="false" Priority="34" QFormat="true"
   Name="List Paragraph"/>
  <w:LsdException Locked="false" Priority="29" QFormat="true" Name="Quote"/>
  <w:LsdException Locked="false" Priority="30" QFormat="true"
   Name="Intense Quote"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 1"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 1"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 2"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 2"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 2"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 3"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 3"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 3"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 4"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 4"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 4"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 5"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 5"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 5"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 6"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 6"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 6"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="19" QFormat="true"
   Name="Subtle Emphasis"/>
  <w:LsdException Locked="false" Priority="21" QFormat="true"
   Name="Intense Emphasis"/>
  <w:LsdException Locked="false" Priority="31" QFormat="true"
   Name="Subtle Reference"/>
  <w:LsdException Locked="false" Priority="32" QFormat="true"
   Name="Intense Reference"/>
  <w:LsdException Locked="false" Priority="33" QFormat="true" Name="Book Title"/>
  <w:LsdException Locked="false" Priority="37" SemiHidden="true"
   UnhideWhenUsed="true" Name="Bibliography"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="TOC Heading"/>
  <w:LsdException Locked="false" Priority="41" Name="Plain Table 1"/>
  <w:LsdException Locked="false" Priority="42" Name="Plain Table 2"/>
  <w:LsdException Locked="false" Priority="43" Name="Plain Table 3"/>
  <w:LsdException Locked="false" Priority="44" Name="Plain Table 4"/>
  <w:LsdException Locked="false" Priority="45" Name="Plain Table 5"/>
  <w:LsdException Locked="false" Priority="40" Name="Grid Table Light"/>
  <w:LsdException Locked="false" Priority="46" Name="Grid Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="Grid Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="Grid Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="46" Name="List Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="List Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="List Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 6"/>
 </w:LatentStyles>
</xml><![endif]-->
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Wingdings;
	panose-1:5 0 0 0 0 0 0 0 0 0;
	mso-font-charset:2;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:0 268435456 0 0 -2147483648 0;}
@font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-536869121 1107305727 33554432 0 415 0;}
@font-face
	{font-family:"Calibri Light";
	panose-1:2 15 3 2 2 2 4 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-469750017 -1073732485 9 0 511 0;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-469750017 -1073732485 9 0 511 0;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-parent:"";
	margin:0cm;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;}
h2
	{mso-style-noshow:yes;
	mso-style-priority:9;
	mso-style-qformat:yes;
	mso-style-link:"Heading 2 Char";
	mso-style-next:Normal;
	margin-top:2.0pt;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:0cm;
	margin-bottom:.0001pt;
	line-height:105%;
	mso-pagination:widow-orphan lines-together;
	page-break-after:avoid;
	mso-outline-level:2;
	font-size:13.0pt;
	font-family:"Calibri Light","sans-serif";
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#2E74B5;
	mso-themecolor:accent1;
	mso-themeshade:191;
	mso-fareast-language:EN-US;
	font-weight:normal;}
p
	{mso-style-priority:99;
	mso-margin-top-alt:auto;
	margin-right:0cm;
	mso-margin-bottom-alt:auto;
	margin-left:0cm;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";}
p.MsoListParagraph, li.MsoListParagraph, div.MsoListParagraph
	{mso-style-noshow:yes;
	mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:36.0pt;
	mso-add-space:auto;
	line-height:105%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
p.MsoListParagraphCxSpFirst, li.MsoListParagraphCxSpFirst, div.MsoListParagraphCxSpFirst
	{mso-style-noshow:yes;
	mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	line-height:105%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
p.MsoListParagraphCxSpMiddle, li.MsoListParagraphCxSpMiddle, div.MsoListParagraphCxSpMiddle
	{mso-style-noshow:yes;
	mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	line-height:105%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
p.MsoListParagraphCxSpLast, li.MsoListParagraphCxSpLast, div.MsoListParagraphCxSpLast
	{mso-style-noshow:yes;
	mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:36.0pt;
	mso-add-space:auto;
	line-height:105%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri","sans-serif";
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:Calibri;
	mso-fareast-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
span.Heading2Char
	{mso-style-name:"Heading 2 Char";
	mso-style-noshow:yes;
	mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:"Heading 2";
	mso-ansi-font-size:13.0pt;
	mso-bidi-font-size:13.0pt;
	font-family:"Calibri Light","sans-serif";
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#2E74B5;
	mso-themecolor:accent1;
	mso-themeshade:191;
	mso-fareast-language:EN-US;}
span.SpellE
	{mso-style-name:"";
	mso-spl-e:yes;}
span.GramE
	{mso-style-name:"";
	mso-gram-e:yes;}
.MsoChpDefault
	{mso-style-type:export-only;
	mso-default-props:yes;
	font-size:10.0pt;
	mso-ansi-font-size:10.0pt;
	mso-bidi-font-size:10.0pt;}
@page WordSection1
	{size:595.3pt 841.9pt;
	margin:72.0pt 72.0pt 72.0pt 72.0pt;
	mso-header-margin:35.4pt;
	mso-footer-margin:35.4pt;
	mso-paper-source:0;}
div.WordSection1
	{page:WordSection1;}
 /* List Definitions */
 @list l0
	{mso-list-id:736821391;
	mso-list-type:hybrid;
	mso-list-template-ids:1237462426 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l0:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l0:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l0:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l0:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l0:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l0:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l0:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l0:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l0:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l1
	{mso-list-id:1870489364;
	mso-list-type:hybrid;
	mso-list-template-ids:1842751066 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l1:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l1:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:90.0pt;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l1:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:126.0pt;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l1:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:162.0pt;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l1:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:198.0pt;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l1:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:234.0pt;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l1:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:270.0pt;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l1:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:306.0pt;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l1:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:342.0pt;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l2
	{mso-list-id:1924531344;
	mso-list-type:hybrid;
	mso-list-template-ids:-282417962 509879886 1074331673 1074331675 1074331663 1074331673 1074331675 1074331663 1074331673 1074331675;}
@list l2:level1
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-weight:bold;}
@list l2:level2
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l2:level3
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l2:level4
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l2:level5
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l2:level6
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l2:level7
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l2:level8
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l2:level9
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l3
	{mso-list-id:1955748788;
	mso-list-type:hybrid;
	mso-list-template-ids:1753246816 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l3:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l3:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:90.0pt;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l3:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:126.0pt;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l3:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:162.0pt;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l3:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:198.0pt;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l3:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:234.0pt;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l3:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:270.0pt;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l3:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:306.0pt;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l3:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:342.0pt;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l4
	{mso-list-id:2130971545;
	mso-list-template-ids:726427502;}
@list l4:level1
	{mso-level-text:%1;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:18.0pt;
	text-indent:-18.0pt;
	mso-ansi-font-weight:bold;}
@list l4:level2
	{mso-level-text:"%1\.%2";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:18.0pt;
	text-indent:-18.0pt;
	mso-ansi-font-weight:bold;}
@list l4:level3
	{mso-level-text:"%1\.%2\.%3";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;
	mso-ansi-font-weight:bold;}
@list l4:level4
	{mso-level-text:"%1\.%2\.%3\.%4";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:36.0pt;
	text-indent:-36.0pt;
	mso-ansi-font-weight:bold;}
@list l4:level5
	{mso-level-text:"%1\.%2\.%3\.%4\.%5";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;
	mso-ansi-font-weight:bold;}
@list l4:level6
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-54.0pt;
	mso-ansi-font-weight:bold;}
@list l4:level7
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;
	mso-ansi-font-weight:bold;}
@list l4:level8
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:72.0pt;
	text-indent:-72.0pt;
	mso-ansi-font-weight:bold;}
@list l4:level9
	{mso-level-text:"%1\.%2\.%3\.%4\.%5\.%6\.%7\.%8\.%9";
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:90.0pt;
	text-indent:-90.0pt;
	mso-ansi-font-weight:bold;}
ol
	{margin-bottom:0cm;}
ul
	{margin-bottom:0cm;}
-->
</style>
<!--[if gte mso 10]>
<style>
 /* Style Definitions */
 table.MsoNormalTable
	{mso-style-name:"Table Normal";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-parent:"";
	mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
	mso-para-margin:0cm;
	mso-para-margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:10.0pt;
	font-family:"Times New Roman","serif";}
</style>
<![endif]--><!--[if gte mso 9]><xml>
 <o:shapedefaults v:ext="edit" spidmax="1026"/>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <o:shapelayout v:ext="edit">
  <o:idmap v:ext="edit" data="1"/>
 </o:shapelayout></xml><![endif]-->
</head>

<body lang=EN-IN style='tab-interval:36.0pt'>

<div class=WordSection1>

<h2 style='margin-top:0cm;line-height:150%;background:white'><b
style='mso-bidi-font-weight:normal'><span style='font-size:14.0pt;line-height:
150%;font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black;mso-font-kerning:18.0pt'>Type</span></b><b><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
mso-font-kerning:18.0pt'> </span></b><b style='mso-bidi-font-weight:normal'><span
style='font-size:14.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black;
mso-font-kerning:18.0pt'>Coercion</span></b><b><span style='font-size:12.0pt;
line-height:150%;font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;mso-font-kerning:18.0pt'><o:p></o:p></span></b></h2>

<p class=MsoNormal style='text-align:justify;line-height:150%'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:Calibri;mso-fareast-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>Content</span></b><b><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;mso-font-kerning:18.0pt'><o:p></o:p></span></b></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><b><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;mso-font-kerning:18.0pt'>1. What
is Type Coercion?<o:p></o:p></span></b></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'>1.1 <span
style='mso-bidi-font-weight:bold'>Number to </span>String<strong><span
style='color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm;background:white'> </span></strong><span
style='mso-bidi-font-weight:bold'>Conversion</span><span style='color:#273239;
letter-spacing:.1pt;background:white'><o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='mso-bidi-font-weight:bold'>1.2 String<strong><span style='color:#273239;
letter-spacing:.1pt;border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;
padding:0cm'> </span></strong></span>to<strong><span style='color:#273239;
letter-spacing:.1pt;border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;
padding:0cm'> </span></strong>Number<strong><span style='color:#273239;
letter-spacing:.1pt;border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;
padding:0cm'> </span></strong><span style='mso-bidi-font-weight:bold'>Conversion<strong><span
style='color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm'><o:p></o:p></span></strong></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='mso-bidi-font-weight:bold'>1.3 Boolean<strong><span style='color:#273239;
letter-spacing:.1pt;border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;
padding:0cm'> </span></strong>to<strong><span style='color:#273239;letter-spacing:
.1pt;border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;
padding:0cm'> </span></strong></span>Number <span style='mso-bidi-font-weight:
bold'>Conversion<strong><span style='color:#273239;letter-spacing:.1pt;
border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;padding:0cm'><o:p></o:p></span></strong></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'>1.4 The<strong><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt;border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;
padding:0cm;font-weight:normal;mso-bidi-font-weight:bold'> </span></strong><span
style='mso-bidi-font-weight:bold'>Equality</span><strong><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt;border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;
padding:0cm;font-weight:normal;mso-bidi-font-weight:bold'> </span></strong>Operator<b
style='mso-bidi-font-weight:normal'><span style='mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin'><o:p></o:p></span></b></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin'>2. References</span></b><b style='mso-bidi-font-weight:normal'><span
style='mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin'><o:p></o:p></span></b></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><b><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
mso-font-kerning:18.0pt'>1. What is Type Coercion?<o:p></o:p></span></b></h2>

<p class=MsoListParagraphCxSpFirst style='text-align:justify;text-indent:-7.65pt;
line-height:150%;mso-list:l0 level1 lfo3'><![if !supportLists]><span
style='font-size:12.0pt;line-height:150%;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol;color:#273239;letter-spacing:.1pt'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><strong><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm;background:white'>Type Coercion</span></strong><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;background:
white'>&nbsp;refers to the process of automatic or implicit conversion of
values from one data type to another. </span><span style='font-size:12.0pt;
line-height:150%;mso-fareast-font-family:"Times New Roman";mso-fareast-theme-font:
minor-fareast;mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;
color:#273239;letter-spacing:.1pt;background:white'><o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-7.65pt;
line-height:150%;mso-list:l0 level1 lfo3'><![if !supportLists]><span
style='font-size:12.0pt;line-height:150%;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol;color:#273239;letter-spacing:.1pt'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;background:
white'>This includes conversion from Number to String, String to Number,
Boolean to Number etc. when different types of operators are applied to the
values.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast style='text-align:justify;text-indent:-7.65pt;
line-height:150%;mso-list:l0 level1 lfo3'><![if !supportLists]><span
style='font-size:12.0pt;line-height:150%;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol;color:#273239;letter-spacing:.1pt'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;background:
white'>In case the behaviour of the implicit conversion is not sure, the
constructors of a data type can be used to convert any value to that <span
class=SpellE>datatype</span>, like the&nbsp;<strong><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm'>Number()</span></strong>,&nbsp;<strong><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm'>String()&nbsp;</span></strong>or&nbsp;<strong><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm'>Boolean()</span></strong>&nbsp;constructor.<o:p></o:p></span></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><strong><span
style='font-family:"Calibri Light","sans-serif";mso-ascii-theme-font:major-latin;
mso-hansi-theme-font:major-latin;mso-bidi-font-family:Calibri;mso-bidi-theme-font:
minor-latin;color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm;background:white'>1.1 </span></strong><strong><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri Light","sans-serif";
mso-ascii-theme-font:major-latin;mso-hansi-theme-font:major-latin;mso-bidi-font-family:
Calibri;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;
border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;padding:0cm;
background:white'>Number to String Conversion</span></strong><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;background:
white'><o:p></o:p></span></h2>

<p class=MsoListParagraphCxSpFirst style='margin-left:54.0pt;mso-add-space:
auto;text-align:justify;text-indent:-11.45pt;line-height:150%;mso-list:l1 level1 lfo4'><![if !supportLists]><span
style='font-size:12.0pt;line-height:150%;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol;color:#273239;letter-spacing:.1pt'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span style='font-size:12.0pt;line-height:150%;
mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt;background:white'>When any string or non-string value is
added to a string, it always converts the non-string value to a string
implicitly. <o:p></o:p></span></p>

<p class=MsoListParagraphCxSpLast style='margin-left:54.0pt;mso-add-space:auto;
text-align:justify;text-indent:-11.45pt;line-height:150%;mso-list:l1 level1 lfo4'><![if !supportLists]><span
style='font-size:12.0pt;line-height:150%;font-family:Symbol;mso-fareast-font-family:
Symbol;mso-bidi-font-family:Symbol;color:#273239;letter-spacing:.1pt'><span
style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span style='font-size:12.0pt;line-height:150%;
mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt;background:white'>When the string </span><span
style='font-size:12.0pt;line-height:150%;mso-fareast-font-family:"Times New Roman";
mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt'>'</span><span style='font-size:12.0pt;line-height:150%;
mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt;background:white'>Rahul</span><span style='font-size:12.0pt;
line-height:150%;mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
Calibri;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>'</span><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;background:
white'> is added to the number 10 then JavaScript does not give an error. It
converts the number 10 to string </span><span style='font-size:12.0pt;
line-height:150%;mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
Calibri;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>'</span><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;background:
white'>10</span><span style='font-size:12.0pt;line-height:150%;mso-fareast-font-family:
"Times New Roman";mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;
color:#273239;letter-spacing:.1pt'>'</span><span style='font-size:12.0pt;
line-height:150%;mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;
color:#273239;letter-spacing:.1pt;background:white'> using coercion and then
concatenates both the strings.<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:#273239;letter-spacing:.1pt;background:white'>Example<o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&lt;<span
class=GramE>script</span>&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;<span
style='mso-spacerun:yes'>        </span><span class=SpellE><span class=GramE>var</span></span>
x = 10 + '20'; <span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'>           </span><span
style='mso-spacerun:yes'>       </span><span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'> </span><span style='mso-spacerun:yes'>  </span><span
style='mso-spacerun:yes'> </span>// The Number 10 is converted to<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;<span
style='mso-spacerun:yes'>        </span>&nbsp;<span class=SpellE><span
class=GramE>var</span></span> y = '20' + 10;<span style='mso-spacerun:yes'>  
</span><span style='mso-spacerun:yes'>                    </span>// string '10'
and then '+' concatenates both strings&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'><span
style='mso-spacerun:yes'>        </span>&nbsp;<span class=SpellE><span
class=GramE>var</span></span> z = true + '10';<span
style='mso-spacerun:yes'>     </span><span
style='mso-spacerun:yes'>            </span><span
style='mso-spacerun:yes'>  </span>// The Boolean value true is converted<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'><span
style='mso-spacerun:yes'>           </span><span
style='mso-spacerun:yes'>                                           </span><span
style='mso-spacerun:yes'>  </span>// string 'true' and then '+' concatenates
both the strings<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE>document.write</span>(x);<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>document.write</span></span><span class=GramE>(</span>&quot;&lt;<span
class=SpellE>br</span>&gt;&quot;);<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE>document.write</span>(y);<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>document.write</span></span><span class=GramE>(</span>&quot;&lt;<span
class=SpellE>br</span>&gt;&quot;);<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>document.write</span></span><span class=GramE>(</span>z);<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&lt;/script&gt;<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt'>Output<o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>1020<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>2010<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>True10<o:p></o:p></span></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><strong><span
style='font-family:"Calibri Light","sans-serif";mso-ascii-theme-font:major-latin;
mso-hansi-theme-font:major-latin;mso-bidi-font-family:Calibri;mso-bidi-theme-font:
minor-latin;color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm;background:white'>1.2 </span></strong><strong><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm;background:white'>String</span></strong><strong><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm'> to Number Conversion<o:p></o:p></span></strong></h2>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:54.0pt;
margin-bottom:.0001pt;text-align:justify;text-indent:-11.45pt;line-height:150%;
mso-list:l3 level1 lfo6;background:white;vertical-align:baseline'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#273239;letter-spacing:.1pt'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span></span></span><![endif]><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt'>When an operation like subtraction (-), multiplication
(*), division (/) or modulus (%) is performed, all the values that are not
number are converted into the number data type, as these operations can be performed
between numbers only.<o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;text-align:justify;line-height:150%;
background:white;vertical-align:baseline'><strong><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;
border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;padding:0cm'>Example</span></strong><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt'><o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&lt;<span
class=GramE>script</span>&gt;&nbsp;&nbsp;&nbsp;&nbsp;<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'><span
style='mso-spacerun:yes'>       </span>&nbsp;<span class=SpellE><span
class=GramE>var</span></span> w = 10 - '5';<span
style='mso-spacerun:yes'>                                    </span><span
style='mso-spacerun:yes'> </span>// The string '5' is converted<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>                                                             
</span>&nbsp;&nbsp;// to number 5 in all cases implicitly<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>var</span></span> x = 10 * '5';<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>var</span></span> y = 10 / '5';<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>var</span></span> z = 10 % '5';<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>document.write</span></span><span class=GramE>(</span>w);<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<span class=SpellE><span class=GramE>document.write</span></span><span
class=GramE>(</span>&quot;&lt;<span class=SpellE>br</span>&gt;&quot;)<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE>document.write</span>(x);<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>document.write</span></span><span class=GramE>(</span>&quot;&lt;<span
class=SpellE>br</span>&gt;&quot;)<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<span class=SpellE>document.write</span>(y);<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>  </span><span class=SpellE><span class=GramE>document.write</span></span><span
class=GramE>(</span>&quot;&lt;<span class=SpellE>br</span>&gt;&quot;)<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>document.write</span></span><span class=GramE>(</span>z);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&lt;/script&gt;<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin'>Output<o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>5<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>50<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>2<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>0<o:p></o:p></span></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><strong><span
style='font-family:"Calibri Light","sans-serif";mso-ascii-theme-font:major-latin;
mso-hansi-theme-font:major-latin;mso-bidi-font-family:Calibri;mso-bidi-theme-font:
minor-latin;color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm;background:white'>1.3 </span></strong><strong><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm;background:white'>Boolean</span></strong><strong><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm'> to Number</span></strong><strong><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt;border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;
padding:0cm'> </span></strong><strong><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm;mso-bidi-font-weight:normal'>Conversion</span></strong><strong><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:#273239;letter-spacing:.1pt;border:none windowtext 1.0pt;
mso-border-alt:none windowtext 0cm;padding:0cm'><o:p></o:p></span></strong></h2>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:54.0pt;
margin-bottom:.0001pt;text-align:justify;text-indent:-11.45pt;line-height:150%;
mso-list:l3 level1 lfo6;background:white;vertical-align:baseline'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#273239;letter-spacing:.1pt'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span></span></span><![endif]><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt'>When a Boolean is added to a Number, the Boolean value is
converted to a number as it is safer and easier to convert Boolean values to
Number values.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:54.0pt;
margin-bottom:.0001pt;text-align:justify;text-indent:-11.45pt;line-height:150%;
mso-list:l3 level1 lfo6;background:white;vertical-align:baseline'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#273239;letter-spacing:.1pt'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span></span></span><![endif]><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt'><span style='mso-spacerun:yes'> </span>A Boolean value can
be represented as 0 for 'false' or 1 for 'true'. <o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;text-align:justify;line-height:150%;
background:white;vertical-align:baseline'><strong><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;
border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;padding:0cm'>Example</span></strong><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt'><o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&lt;<span
class=GramE>script</span>&gt;<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>        </span><span class=SpellE><span class=GramE>var</span></span>
x = true + 2;<span style='mso-spacerun:yes'>    </span><span
style='mso-spacerun:yes'> </span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>                </span>&nbsp;<span
style='mso-spacerun:yes'>   </span>&nbsp;// The Boolean value true is<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>                                                          
</span><span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'> </span><span style='mso-spacerun:yes'> </span>&nbsp;//
converted to number 1 and<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>                                                          
</span>&nbsp;<span style='mso-spacerun:yes'>  </span>&nbsp;// then operation is
performed<span style='mso-spacerun:yes'>                    </span>&nbsp;<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>    </span><span style='mso-spacerun:yes'>   </span><span
style='mso-spacerun:yes'>  </span>&nbsp;<span class=SpellE><span class=GramE>var</span></span>
y = false + 2;<span style='mso-spacerun:yes'>  </span><span
style='mso-spacerun:yes'>                     </span><span
style='mso-spacerun:yes'> </span><span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'>  </span>// The Boolean value false is<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>                                                        
</span>&nbsp;// converted to number 0 and<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>                          </span><span
style='mso-spacerun:yes'>                             </span><span
style='mso-spacerun:yes'> </span>// then operation is performed&nbsp;<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>    </span><span class=SpellE>document.write</span>(x);<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>   </span><span class=SpellE><span class=GramE>document.write</span></span><span
class=GramE>(</span>&quot;&lt;<span class=SpellE>br</span>&gt;&quot;)<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>   </span>&nbsp;<span class=SpellE>document.write</span>(y);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&lt;/script&gt;<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin'>Output<o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>3<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>2<o:p></o:p></span></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><strong><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt;border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;
padding:0cm'>1.4 </span></strong><strong><span style='font-size:12.0pt;
line-height:150%;font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt;border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;
padding:0cm'>The Equality Operator<o:p></o:p></span></strong></h2>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:54.0pt;
margin-bottom:.0001pt;text-align:justify;text-indent:-11.45pt;line-height:150%;
mso-list:l3 level1 lfo6;background:white;vertical-align:baseline'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#273239;letter-spacing:.1pt'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span></span></span><![endif]><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt'>The equality operator (==) can be used to compare values
irrespective of their type. <o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:54.0pt;
margin-bottom:.0001pt;text-align:justify;text-indent:-11.45pt;line-height:150%;
mso-list:l3 level1 lfo6;background:white;vertical-align:baseline'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#273239;letter-spacing:.1pt'><span style='mso-list:Ignore'>·<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span></span></span><![endif]><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt'>This is done by coercing a non-number data type to a
number. <o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;text-align:justify;line-height:150%;
background:white;vertical-align:baseline'><strong><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt;
border:none windowtext 1.0pt;mso-border-alt:none windowtext 0cm;padding:0cm'>Example:</span></strong><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:#273239;
letter-spacing:.1pt'><o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&lt;<span
class=GramE>script</span>&gt;<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>var</span></span> x = (10 == '10'); <span
style='mso-spacerun:yes'>                         </span><span
style='mso-spacerun:yes'>   </span><span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'>          </span><span
style='mso-spacerun:yes'>   </span><span style='mso-spacerun:yes'> </span>//
Should output 'true' as string '10'<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>                                                                  
</span><span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'> </span><span style='mso-spacerun:yes'>     </span><span
style='mso-spacerun:yes'>  </span>// is coerced to number 10<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>   </span>&nbsp;&nbsp;<span class=SpellE><span
class=GramE>var</span></span> y = (true == 1);<span
style='mso-spacerun:yes'>    </span><span
style='mso-spacerun:yes'>        </span><span
style='mso-spacerun:yes'>           </span><span
style='mso-spacerun:yes'>             </span><span
style='mso-spacerun:yes'>  </span><span style='mso-spacerun:yes'> </span><span
style='mso-spacerun:yes'> </span><span style='mso-spacerun:yes'> </span>//
Should output 'true', as Boolean true<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>                                                           
</span><span style='mso-spacerun:yes'>    </span><span
style='mso-spacerun:yes'>       </span><span style='mso-spacerun:yes'> </span>//
is coerced to number 1<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<span style='mso-spacerun:yes'> </span><span class=SpellE><span class=GramE>var</span></span>
z = (true == 'true'); <span
style='mso-spacerun:yes'>                           </span><span
style='mso-spacerun:yes'> </span><span style='mso-spacerun:yes'> </span>//
Should output 'false' as string 'true'<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>                                         </span><span
style='mso-spacerun:yes'>                           </span>// is coerced to <span
class=SpellE>NaN</span> which is not equal to<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
style='mso-spacerun:yes'>                        </span><span
style='mso-spacerun:yes'>              </span><span
style='mso-spacerun:yes'>                           </span><span
style='mso-spacerun:yes'> </span>// 1 of Boolean true<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE>document.write</span>(x);<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>document.write</span></span><span class=GramE>(</span>&quot;&lt;<span
class=SpellE>br</span>&gt;&quot;);<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE>document.write</span>(y);<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>document.write</span></span><span class=GramE>(</span>&quot;&lt;<span
class=SpellE>br</span>&gt;&quot;);<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span
class=SpellE><span class=GramE>document.write</span></span><span class=GramE>(</span>z);<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'>&nbsp;&nbsp;&nbsp;&nbsp;&lt;/script&gt;<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin'>Output</span></b><b style='mso-bidi-font-weight:normal'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:#273239;letter-spacing:.1pt'><o:p></o:p></span></b></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>True<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>True<o:p></o:p></span></p>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>False<o:p></o:p></span></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><b
style='mso-bidi-font-weight:normal'><span style='font-size:12.0pt;line-height:
150%;font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>2. References<o:p></o:p></span></b></h2>

<p class=MsoNormal style='margin-left:18.0pt;text-align:justify;line-height:
150%'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>1.
https://www.geeksforgeeks.org/what-is-type-coercion-in-javascript/<o:p></o:p></span></p>

<p class=MsoNormal style='text-align:justify;line-height:150%'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'><o:p>&nbsp;</o:p></span></p>

</div>

</body>

</html>
