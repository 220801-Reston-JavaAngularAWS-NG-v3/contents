<html xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word"
xmlns:m="http://schemas.microsoft.com/office/2004/12/omml"
xmlns="http://www.w3.org/TR/REC-html40">

<head>
<meta http-equiv=Content-Type content="text/html; charset=us-ascii">
<meta name=ProgId content=Word.Document>
<meta name=Generator content="Microsoft Word 15">
<meta name=Originator content="Microsoft Word 15">
<link rel=File-List href="12-JS-timing-events_files/filelist.xml">
<!--[if gte mso 9]><xml>
 <o:DocumentProperties>
  <o:Author>Balaji</o:Author>
  <o:Template>Normal</o:Template>
  <o:LastAuthor>Balaji</o:LastAuthor>
  <o:Revision>32</o:Revision>
  <o:TotalTime>70</o:TotalTime>
  <o:Created>2022-08-19T04:36:00Z</o:Created>
  <o:LastSaved>2022-08-19T07:27:00Z</o:LastSaved>
  <o:Pages>4</o:Pages>
  <o:Words>489</o:Words>
  <o:Characters>2790</o:Characters>
  <o:Lines>23</o:Lines>
  <o:Paragraphs>6</o:Paragraphs>
  <o:CharactersWithSpaces>3273</o:CharactersWithSpaces>
  <o:Version>15.00</o:Version>
 </o:DocumentProperties>
 <o:OfficeDocumentSettings>
  <o:AllowPNG/>
 </o:OfficeDocumentSettings>
</xml><![endif]-->
<link rel=themeData href="12-JS-timing-events_files/themedata.thmx">
<link rel=colorSchemeMapping
href="12-JS-timing-events_files/colorschememapping.xml">
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
	{mso-style-priority:9;
	mso-style-qformat:yes;
	mso-style-link:"Heading 2 Char";
	mso-style-next:Normal;
	margin-top:2.0pt;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:0cm;
	margin-bottom:.0001pt;
	line-height:106%;
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
h3
	{mso-style-noshow:yes;
	mso-style-priority:9;
	mso-style-qformat:yes;
	mso-style-link:"Heading 3 Char";
	mso-style-next:Normal;
	margin-top:2.0pt;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:0cm;
	margin-bottom:.0001pt;
	line-height:106%;
	mso-pagination:widow-orphan lines-together;
	page-break-after:avoid;
	mso-outline-level:3;
	font-size:12.0pt;
	font-family:"Calibri Light","sans-serif";
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#1F4D78;
	mso-themecolor:accent1;
	mso-themeshade:127;
	mso-fareast-language:EN-US;
	font-weight:normal;}
p
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-margin-top-alt:auto;
	margin-right:0cm;
	mso-margin-bottom-alt:auto;
	margin-left:0cm;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman","serif";
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:minor-fareast;}
code
	{mso-style-noshow:yes;
	mso-style-priority:99;
	font-family:"Courier New";
	mso-ascii-font-family:"Courier New";
	mso-fareast-font-family:"Times New Roman";
	mso-hansi-font-family:"Courier New";
	mso-bidi-font-family:"Courier New";}
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
	line-height:106%;
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
	line-height:106%;
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
	line-height:106%;
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
	line-height:106%;
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
span.Heading3Char
	{mso-style-name:"Heading 3 Char";
	mso-style-noshow:yes;
	mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:"Heading 3";
	mso-ansi-font-size:12.0pt;
	mso-bidi-font-size:12.0pt;
	font-family:"Calibri Light","sans-serif";
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#1F4D78;
	mso-themecolor:accent1;
	mso-themeshade:127;
	mso-fareast-language:EN-US;}
span.tagnamecolor
	{mso-style-name:tagnamecolor;
	mso-style-unhide:no;}
span.tagcolor
	{mso-style-name:tagcolor;
	mso-style-unhide:no;}
span.attributecolor
	{mso-style-name:attributecolor;
	mso-style-unhide:no;}
span.attributevaluecolor
	{mso-style-name:attributevaluecolor;
	mso-style-unhide:no;}
span.jscolor
	{mso-style-name:jscolor;
	mso-style-unhide:no;}
span.jskeywordcolor
	{mso-style-name:jskeywordcolor;
	mso-style-unhide:no;}
span.jsstringcolor
	{mso-style-name:jsstringcolor;
	mso-style-unhide:no;}
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
	{mso-list-id:107430161;
	mso-list-template-ids:-1788961790;}
@list l0:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l0:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:"Courier New";
	mso-bidi-font-family:"Times New Roman";}
@list l0:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l0:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l0:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l0:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l0:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l0:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l0:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l1
	{mso-list-id:471211882;
	mso-list-type:hybrid;
	mso-list-template-ids:1671850944 1074331663 1074331673 1074331675 1074331663 1074331673 1074331675 1074331663 1074331673 1074331675;}
@list l1:level1
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level2
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level3
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l1:level4
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level5
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level6
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l1:level7
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level8
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level9
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l2
	{mso-list-id:607859483;
	mso-list-type:hybrid;
	mso-list-template-ids:591670396 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l2:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l2:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l2:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l2:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l2:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l2:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l2:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l2:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l2:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l3
	{mso-list-id:668143123;
	mso-list-template-ids:947438864;}
@list l3:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l3:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l3:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l3:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l3:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l3:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l3:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l3:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l3:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l4
	{mso-list-id:691614096;
	mso-list-type:hybrid;
	mso-list-template-ids:1008113106 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l4:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l4:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l4:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l4:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l4:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l4:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l4:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l4:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l4:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l5
	{mso-list-id:810903854;
	mso-list-template-ids:-724669012;}
@list l5:level1
	{mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;}
@list l5:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:"Courier New";
	mso-bidi-font-family:"Times New Roman";}
@list l5:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l5:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l5:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l5:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l5:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l5:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l5:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l6
	{mso-list-id:996495989;
	mso-list-type:hybrid;
	mso-list-template-ids:1278138140 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l6:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l6:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l6:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l6:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l6:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l6:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l6:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l6:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l6:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l7
	{mso-list-id:1089618434;
	mso-list-type:hybrid;
	mso-list-template-ids:839964418 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l7:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l7:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l7:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l7:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l7:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l7:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l7:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l7:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l7:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l8
	{mso-list-id:1092313823;
	mso-list-template-ids:-1210934284;}
@list l8:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l8:level2
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l8:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l8:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l8:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l8:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l8:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l8:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l8:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Symbol;}
@list l9
	{mso-list-id:1441559796;
	mso-list-type:hybrid;
	mso-list-template-ids:453920538 1074331663 1074331673 1074331675 1074331663 1074331673 1074331675 1074331663 1074331673 1074331675;}
@list l9:level1
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l9:level2
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l9:level3
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l9:level4
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l9:level5
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l9:level6
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l9:level7
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l9:level8
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l9:level9
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l10
	{mso-list-id:1564095943;
	mso-list-type:hybrid;
	mso-list-template-ids:-2134368180 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l10:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l10:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l10:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l10:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l10:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l10:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l10:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l10:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l10:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l11
	{mso-list-id:1683387383;
	mso-list-template-ids:-724669012;}
@list l11:level1
	{mso-level-tab-stop:36.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;}
@list l11:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:72.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:"Courier New";
	mso-bidi-font-family:"Times New Roman";}
@list l11:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:108.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l11:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:144.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l11:level5
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:180.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l11:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:216.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l11:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:252.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l11:level8
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:288.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l11:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:324.0pt;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	mso-ansi-font-size:10.0pt;
	font-family:Wingdings;}
@list l12
	{mso-list-id:1787656428;
	mso-list-type:hybrid;
	mso-list-template-ids:-1952826162 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l12:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l12:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l12:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l12:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l12:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l12:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l12:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l12:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l12:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l13
	{mso-list-id:2021007383;
	mso-list-type:hybrid;
	mso-list-template-ids:-290668550 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l13:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l13:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l13:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l13:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l13:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l13:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l13:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l13:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l13:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l14
	{mso-list-id:2071607360;
	mso-list-type:hybrid;
	mso-list-template-ids:1203908410 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653 1074331649 1074331651 1074331653;}
@list l14:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l14:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l14:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l14:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l14:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l14:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l14:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l14:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l14:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
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

<p class=MsoNormal style='line-height:150%;mso-outline-level:1;background:white'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black;
mso-font-kerning:18.0pt'>JS&nbsp;Timing Events<o:p></o:p></span></b></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:white'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black;
mso-font-kerning:18.0pt'>Content<o:p></o:p></span></b></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:white'><b><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>1.
Timing Events</span></b><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'><o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:white'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black;
mso-bidi-font-weight:bold'>1.2 The <span class=SpellE><span class=GramE>setTimeout</span></span><span
class=GramE>(</span>) Method<o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:white'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black;
mso-bidi-font-weight:bold'>1.2.1 How to <span class=GramE>Stop</span> <span
class=SpellE>setTimeout</span> Execution?</span><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black;mso-fareast-language:EN-US'><o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:white'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black;
mso-bidi-font-weight:bold'>1.3 The <span class=SpellE><span class=GramE>setInterval</span></span><span
class=GramE>(</span>) Method</span><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-fareast-theme-font:major-fareast;mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'><o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:white'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black;
mso-bidi-font-weight:bold'>1.3.1 How to Stop <span class=SpellE><span
class=GramE>setInterval</span></span><span class=GramE> <span
style='mso-spacerun:yes'>&nbsp;</span>Execution</span>?</span><o:p></o:p></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:white'><b><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>2.
References</span></b><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'><o:p></o:p></span></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><b><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>1. Timing Events</span></b><span style='font-size:
12.0pt;line-height:150%;font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:black'><o:p></o:p></span></h2>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l0 level1 lfo7;
tab-stops:list 36.0pt;background:white'><![if !supportLists]><span
style='font-size:10.0pt;mso-bidi-font-size:12.0pt;line-height:150%;font-family:
Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The window&nbsp;object allows execution of code at
specified time intervals.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l0 level1 lfo7;
tab-stops:list 36.0pt;background:white'><![if !supportLists]><span
style='font-size:10.0pt;mso-bidi-font-size:12.0pt;line-height:150%;font-family:
Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>These time intervals are called timing events.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l0 level1 lfo7;
tab-stops:list 36.0pt;background:white'><![if !supportLists]><span
style='font-size:10.0pt;mso-bidi-font-size:12.0pt;line-height:150%;font-family:
Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The two key methods to use with JavaScript are:<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-14.7pt;line-height:150%;mso-list:l9 level1 lfo17;
background:#E7E9EB'><![if !supportLists]><b style='mso-bidi-font-weight:normal'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:Calibri;mso-fareast-theme-font:minor-latin;mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin'><span style='mso-list:Ignore'>1.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span></span></span></b><![endif]><span
class=SpellE><b><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:black'>setTimeout</span></b></span><b><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>(f<i>unction</i></span></b><em><b style='mso-bidi-font-weight:
normal'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>,
</span></b></em><b><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:black'>milliseconds</span></b><b style='mso-bidi-font-weight:normal'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>)<o:p></o:p></span></b></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-14.7pt;line-height:150%;mso-list:l9 level1 lfo17;
background:#E7E9EB'><![if !supportLists]><b style='mso-bidi-font-weight:normal'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:Calibri;mso-fareast-theme-font:minor-latin;mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin'><span style='mso-list:Ignore'>2.<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp; </span></span></span></b><![endif]><span
class=SpellE><b><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:black'>setInterval</span></b></span><b><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>(f<i>unction</i></span></b><em><b style='mso-bidi-font-weight:
normal'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>,
</span></b></em><b><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:black'>milliseconds</span></b><b style='mso-bidi-font-weight:normal'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>)<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:150%;background:#FFFFCC'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin'>Note:<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:150%;background:#FFFFCC'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>The&nbsp;</span><span
class=SpellE><span class=GramE>setTimeout</span></span><span class=GramE>(</span>)<span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin'>&nbsp;and&nbsp;</span><span
class=SpellE>setInterval</span>() <span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin'>are <span style='color:black'>both methods of the HTML DOM Window
object.<o:p></o:p></span></span></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><b><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>1.2 The <span class=SpellE><span class=GramE>setTimeout</span></span><span
class=GramE>(</span>) Method<o:p></o:p></span></b></h2>

<p class=MsoListParagraph style='margin-bottom:0cm;margin-bottom:.0001pt;
mso-add-space:auto;text-indent:-7.65pt;line-height:150%;mso-list:l2 level1 lfo9;
background:white'><![if !supportLists]><span style='font-size:12.0pt;
line-height:150%;font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:black;mso-fareast-language:EN-IN'><span style='mso-list:Ignore'>&middot;<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:black'>Executes a function, after waiting
a specified number of milliseconds.</span><span style='font-size:12.0pt;
line-height:150%;mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;
color:black;mso-fareast-language:EN-IN'><o:p></o:p></span></p>

<p class=MsoNormal style='line-height:150%'><b style='mso-bidi-font-weight:
normal'><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
mso-fareast-language:EN-US'>Syntax<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:150%;background:white'><span
class=SpellE><span class=GramE><b style='mso-bidi-font-weight:normal'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>window.setTimeout</span></b></span></span><span
class=GramE><b style='mso-bidi-font-weight:normal'><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:black'>(</span></b></span><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black;mso-bidi-font-style:italic'>function</span></b><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>,<span style='mso-bidi-font-style:italic'>&nbsp;milliseconds</span>);<o:p></o:p></span></b></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l2 level1 lfo9;
background:#E7E9EB'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The&nbsp;</span><span class=SpellE><span class=GramE><span
style='color:black;mso-bidi-font-weight:bold'>window.setTimeout</span></span></span><span
class=GramE><span style='color:black;mso-bidi-font-weight:bold'>(</span></span><span
style='color:black;mso-bidi-font-weight:bold'>)<b> </b></span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>method
can be written without the window prefix.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l2 level1 lfo9;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The first parameter is a function to be executed.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l2 level1 lfo9;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The second parameter indicates the number of milliseconds
before execution.<o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:#E7E9EB'><b><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>Example</span></b><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'><o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l14 level1 lfo15;
background:#E7E9EB'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><b style='mso-bidi-font-weight:normal'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>Click
a button. Wait 3 seconds, and the page will alert &quot;Hello&quot;<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:150%;background:white'><span
class=tagcolor><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:brown'>button</span></span><span
class=attributecolor><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:red'>&nbsp;<span class=SpellE>onclick</span></span></span><span
class=attributevaluecolor><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:mediumblue'>=&quot;<span class=SpellE><span class=GramE>setTimeout</span></span><span
class=GramE>(</span><span class=SpellE>myFunction</span>, 3000)&quot;</span></span><span
class=tagcolor><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:mediumblue'>&gt;</span></span><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>Try it</span><span class=tagcolor><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>&lt;</span></span><span
class=tagnamecolor><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:brown'>/button</span></span><span class=tagcolor><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>&gt;</span></span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'><br>
</span><span class=tagcolor><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:brown'>script</span></span><span
class=tagcolor><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:mediumblue'>&gt;</span></span><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'><br>
</span><span class=jskeywordcolor><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:mediumblue'>function</span></span><span class=jscolor><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>&nbsp;<span
class=SpellE>myFunction</span>() {</span></span><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'><br>
<span class=jscolor>&nbsp;&nbsp;alert(</span></span><span class=jsstringcolor><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:brown'>'Hello'</span></span><span
class=jscolor><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:black'>);</span></span><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'><br>
<span class=jscolor>}</span><br>
</span><span class=tagcolor><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:mediumblue'>&lt;</span></span><span class=tagnamecolor><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:brown'>/script</span></span><span
class=tagcolor><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:mediumblue'>&gt;</span></span><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'><o:p></o:p></span></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><b><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>1.2.1 How to <span class=GramE>Stop</span> <span
class=SpellE>setTimeout</span> Execution?</span></b><span style='font-size:
12.0pt;line-height:150%;font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:black'><o:p></o:p></span></h2>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l7 level1 lfo12;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The&nbsp;</span><span class=SpellE><span class=GramE><span
style='color:black'>clearTimeout</span></span></span><span class=GramE><span
style='color:black'>(</span></span><span style='color:black'>)</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>&nbsp;method
stops the execution of the function specified in <span class=SpellE>setTimeout</span>().<o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:white'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>Syntax<o:p></o:p></span></b></p>

<p class=MsoListParagraph style='line-height:150%;background:white'><span
class=SpellE><span class=GramE><b style='mso-bidi-font-weight:normal'><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:black'>window.clearTimeout</span></b></span></span><span
class=GramE><b style='mso-bidi-font-weight:normal'><span style='font-size:12.0pt;
line-height:150%;mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;
color:black'>(</span></b></span><span class=SpellE><em><b style='mso-bidi-font-weight:
normal'><span style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>timeoutVariable</span></b></em></span><b
style='mso-bidi-font-weight:normal'><span style='font-size:12.0pt;line-height:
150%;mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;color:black'>)<o:p></o:p></span></b></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l7 level1 lfo12;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The&nbsp;</span><span class=SpellE><span class=GramE><span
style='color:black'>window.clearTimeout</span></span></span><span class=GramE><span
style='color:black'>(</span></span><span style='color:black'>) </span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>method
can be written without the window prefix.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l7 level1 lfo12;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The&nbsp;</span><span class=SpellE><span
style='color:black'>clearTimeout</span></span><span style='color:black'>()</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>&nbsp;method
uses the variable returned from&nbsp;</span><span class=SpellE><span
style='color:black'>setTimeout</span></span><span style='color:black'>()</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'><o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:white'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>Example-1<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:150%;background:white'><span
class=SpellE><span class=GramE><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>myVar</span></span></span><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:black'> = <span class=SpellE>setTimeout</span>(<i>function</i>,<i>&nbsp;milliseconds</i>);<br>
<span class=SpellE>clearTimeout</span>(<span class=SpellE>myVar</span>);<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l7 level1 lfo12;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>If the function has not already been executed, you can
stop the execution by calling the&nbsp;</span><span class=SpellE><span
style='color:black'>clearTimeout</span></span><span style='color:black'>()</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>&nbsp;method:<o:p></o:p></span></p>

<p class=MsoNormal style='line-height:150%;background:white'><b><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>Example-2</span></b><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'><o:p></o:p></span></p>

<p class=MsoListParagraph style='text-indent:-7.65pt;line-height:150%;
mso-list:l6 level1 lfo11'><![if !supportLists]><span style='font-size:12.0pt;
line-height:150%;font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:black'><span style='mso-list:Ignore'>&middot;<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><b
style='mso-bidi-font-weight:normal'><span style='font-size:12.0pt;line-height:
150%;mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:black'>Same example as above, but with an
added &quot;Stop&quot; button<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:150%;background:white'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>&lt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>button</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:red'>&nbsp;<span class=SpellE>onclick</span></span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>=&quot;<span class=SpellE>myVar</span>
= <span class=SpellE><span class=GramE>setTimeout</span></span><span
class=GramE>(</span><span class=SpellE>myFunction</span>, 3000)&quot;&gt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>Try it</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>&lt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>/button</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>&gt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'><br>
</span><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>&lt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>button</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:red'>&nbsp;<span class=SpellE>onclick</span></span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>=&quot;<span class=SpellE>clearTimeout</span>(<span
class=SpellE>myVar</span>)&quot;&gt;</span><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>Stop
it</span><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>&lt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>/button</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>&gt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'><o:p></o:p></span></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><b><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>1.3 The <span class=SpellE><span class=GramE>setInterval</span></span><span
class=GramE>(</span>) Method</span></b><span style='font-size:12.0pt;
line-height:150%;font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'><o:p></o:p></span></h2>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l6 level1 lfo11;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The&nbsp;</span><span class=SpellE><span class=GramE><span
style='color:black'>setInterval</span></span></span><span class=GramE><span
style='color:black'>(</span></span><span style='color:black'>)</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>&nbsp;method
repeats a given function at every given time-interval.<o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:white'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>Syntax<o:p></o:p></span></b></p>

<p class=MsoListParagraph style='line-height:150%;background:white'><span
class=SpellE><span class=GramE><b style='mso-bidi-font-weight:normal'><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:black'>window.setInterval</span></b></span></span><span
class=GramE><b style='mso-bidi-font-weight:normal'><span style='font-size:12.0pt;
line-height:150%;mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;
color:black'>(</span></b></span><b style='mso-bidi-font-weight:normal'><i><span
style='font-size:12.0pt;line-height:150%;mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:black'>function</span></i></b><b
style='mso-bidi-font-weight:normal'><span style='font-size:12.0pt;line-height:
150%;mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;color:black'>,<i>&nbsp;milliseconds</i>);<o:p></o:p></span></b></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l6 level1 lfo11;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The&nbsp;</span><span class=SpellE><span class=GramE><span
style='color:black'>window.setInterval</span></span></span><span class=GramE><span
style='color:black'>(</span></span><span style='color:black'>)</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>&nbsp;method
can be written without the window prefix.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l6 level1 lfo11;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The first parameter is the function to be executed.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l6 level1 lfo11;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The second parameter indicates the length of the
time-interval between each execution.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l6 level1 lfo11;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>This example executes a function called &quot;<span
class=SpellE>myTimer</span>&quot; once every second (like a digital watch).<o:p></o:p></span></p>

<p class=MsoNormal style='line-height:150%'><b><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>Example</span></b><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'><o:p></o:p></span></p>

<p class=MsoListParagraph style='text-indent:-7.65pt;line-height:150%;
mso-list:l10 level1 lfo16'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><b style='mso-bidi-font-weight:normal'><span
style='mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:black'>Display the current time:<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:150%;background:white'><span
class=SpellE><span class=GramE><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>setInterval</span></span></span><span
class=GramE><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:black'>(</span></span><span
class=SpellE><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:black'>myTimer</span></span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>,&nbsp;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:red'>1000</span><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-fareast-font-family:
"Times New Roman";mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:black'>);<br>
</span><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>function</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>&nbsp;<span class=SpellE>myTimer</span>()
<o:p></o:p></span></p>

<p class=MsoNormal style='line-height:150%;background:white'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>{<br>
<span class=GramE>&nbsp;</span>&nbsp;</span><span class=SpellE><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>const</span></span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>&nbsp;d =&nbsp;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>new</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>&nbsp;Date();<br>
&nbsp; <span class=SpellE>document.getElementById</span>(</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>&quot;demo&quot;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>).<span class=SpellE>innerHTML</span>&nbsp;=
<span class=SpellE>d.toLocaleTimeString</span>();<br>
}<o:p></o:p></span></p>

<p class=MsoNormal style='line-height:150%;background:white'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>Note:<o:p></o:p></span></b></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l13 level1 lfo13;
background:#FFFFCC'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>There are 1000 milliseconds in one second.<o:p></o:p></span></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><b><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>1.3.1 How to <span class=GramE>Stop</span> <span
class=SpellE>setInterval</span> Execution?</span></b><span style='font-size:
12.0pt;line-height:150%;font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:black'><o:p></o:p></span></h2>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l13 level1 lfo13;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The&nbsp;</span><span class=SpellE><span class=GramE><span
style='color:black'>clearInterval</span></span></span><span class=GramE><span
style='color:black'>(</span></span><span style='color:black'>)</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>&nbsp;method
stops the executions of the function specified in the <span class=SpellE>setInterval</span>()
method.<o:p></o:p></span></p>

<p style='margin:0cm;margin-bottom:.0001pt;line-height:150%;background:white'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>Syntax<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:150%;background:white'><span
class=SpellE><span class=GramE><b style='mso-bidi-font-weight:normal'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>window.clearInterval</span></b></span></span><span
class=GramE><b style='mso-bidi-font-weight:normal'><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:black'>(</span></b></span><span
class=SpellE><em><b style='mso-bidi-font-weight:normal'><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:black'>timerVariable</span></b></em></span><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>)<o:p></o:p></span></b></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l13 level1 lfo13;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The&nbsp;</span><span class=SpellE><span class=GramE><span
style='color:black'>window.clearInterval</span></span></span><span class=GramE><span
style='color:black'>(</span></span><span style='color:black'>)</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>&nbsp;method
can be written without the window prefix.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:36.0pt;
margin-bottom:.0001pt;text-indent:-7.65pt;line-height:150%;mso-list:l13 level1 lfo13;
background:white'><![if !supportLists]><span style='font-family:Symbol;
mso-fareast-font-family:Symbol;mso-bidi-font-family:Symbol;color:black'><span
style='mso-list:Ignore'>&middot;<span style='font:7.0pt "Times New Roman"'>&nbsp;
</span></span></span><![endif]><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>The&nbsp;</span><span class=SpellE><span
style='color:black'>clearInterval</span></span><span style='color:black'>()</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>&nbsp;method
uses the variable returned from&nbsp;</span><span class=SpellE><span
style='color:black'>setInterval</span></span><span style='color:black'>()</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'><o:p></o:p></span></p>

<p class=MsoNormal style='line-height:150%;background:white'><b
style='mso-bidi-font-weight:normal'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>Example-1<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:150%;background:white'><span class=GramE><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>let</span></span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'> <span
class=SpellE>myVar</span> = <span class=SpellE>setInterval</span>(<i>function</i>,<i>&nbsp;milliseconds</i>);<br>
<span class=SpellE>clearInterval</span>(<span class=SpellE>myVar</span>);<o:p></o:p></span></p>

<p class=MsoNormal style='line-height:150%'><b><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>Example-2</span></b><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'><o:p></o:p></span></p>

<p class=MsoListParagraph style='text-indent:-7.65pt;line-height:150%;
mso-list:l4 level1 lfo14'><![if !supportLists]><span style='font-size:12.0pt;
line-height:150%;font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:black'><span style='mso-list:Ignore'>&middot;<span
style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><b
style='mso-bidi-font-weight:normal'><span style='font-size:12.0pt;line-height:
150%;mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:Calibri;
mso-bidi-theme-font:minor-latin;color:black'>Same example as above, but we have
added a &quot;Stop time&quot; button<o:p></o:p></span></b></p>

<p class=MsoNormal style='line-height:150%;background:white'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>&lt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>p</span><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-fareast-font-family:
"Times New Roman";mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:red'>&nbsp;id</span><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>=&quot;demo&quot;&gt;&lt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>/p</span><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-fareast-font-family:
"Times New Roman";mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:mediumblue'>&gt;</span><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'><br>
</span><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>&lt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>button</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:red'>&nbsp;<span class=SpellE>onclick</span></span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>=&quot;<span class=SpellE><span
class=GramE>clearInterval</span></span><span class=GramE>(</span><span
class=SpellE>myVar</span>)&quot;&gt;</span><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-fareast-font-family:"Times New Roman";
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'>Stop
time</span><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>&lt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>/button</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>&gt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'><br>
</span><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>&lt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>script</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>&gt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'><br>
</span><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>let</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>&nbsp;<span class=SpellE>myVar</span>
= <span class=SpellE>setInterval</span>(<span class=SpellE>myTimer</span>,&nbsp;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:red'>1000</span><span style='font-family:
"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;mso-fareast-font-family:
"Times New Roman";mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;
color:black'>);<br>
</span><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>function</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>&nbsp;<span class=SpellE>myTimer</span>()<o:p></o:p></span></p>

<p class=MsoNormal style='line-height:150%;background:white'><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'><span
style='mso-spacerun:yes'>&nbsp;</span>{<br>
<span class=GramE>&nbsp;</span>&nbsp;</span><span class=SpellE><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>const</span></span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>&nbsp;d =&nbsp;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>new</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>&nbsp;Date();<br>
&nbsp; <span class=SpellE>document.getElementById</span>(</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>&quot;demo&quot;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'>).<span class=SpellE>innerHTML</span>&nbsp;=
<span class=SpellE>d.toLocaleTimeString</span>();<br>
}<br>
</span><span style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:
minor-latin;mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:
minor-latin;mso-bidi-theme-font:minor-latin;color:mediumblue'>&lt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:brown'>/script</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:mediumblue'>&gt;</span><span
style='font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-hansi-theme-font:minor-latin;
mso-bidi-theme-font:minor-latin;color:black'><o:p></o:p></span></p>

<h2 style='margin-top:0cm;line-height:150%;background:white'><b><span
style='font-size:12.0pt;line-height:150%;font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin;color:black'>2. References</span></b><span style='font-size:12.0pt;
line-height:150%;font-family:"Calibri","sans-serif";mso-ascii-theme-font:minor-latin;
mso-fareast-font-family:"Times New Roman";mso-fareast-theme-font:minor-fareast;
mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:minor-latin;color:black'><o:p></o:p></span></h2>

<p class=MsoListParagraph style='margin-bottom:0cm;margin-bottom:.0001pt;
mso-add-space:auto;text-indent:-18.0pt;line-height:150%;mso-list:l1 level1 lfo6;
background:white'><![if !supportLists]><span style='font-size:12.0pt;
line-height:150%;mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;
color:black'><span style='mso-list:Ignore'>1.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span style='font-size:12.0pt;line-height:150%;
mso-bidi-font-family:Calibri;mso-bidi-theme-font:minor-latin;color:black'>https://www.w3schools.com/js/js_timing.asp<o:p></o:p></span></p>

<p class=MsoNormal style='line-height:150%'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin'><span style='mso-spacerun:yes'>&nbsp;</span><o:p></o:p></span></p>

<p class=MsoNormal style='line-height:150%'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='line-height:150%'><span style='font-family:"Calibri","sans-serif";
mso-ascii-theme-font:minor-latin;mso-hansi-theme-font:minor-latin;mso-bidi-theme-font:
minor-latin'><o:p>&nbsp;</o:p></span></p>

</div>

</body>

</html>
