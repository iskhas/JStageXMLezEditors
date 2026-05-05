# JStageXMLezEditors
ez xml formatter

- https://www.jstage.jst.go.jp/static/pages/GuidelineAndManuals/zenbun-xml-jats1_1-manual/-char/ja

## string-name
```
      <string-name>
        <surname>山田</surname>
        <given-names>太郎</given-names>
      </string-name>
```

## J-Stage JATS1.1

J-STAGEXML データフォーマットガイドライン
https://www.jstage.jst.go.jp/static/files/ja/jstage_xml_jats1_1_format_guideline.pdf

### サンプル
```
<ref-list>
  <title>参考文献</title>
  <ref id="ref1">
    <mixed-citation publication-type="journal" xlink:type="simple">
      <string-name>
        <surname>山田</surname>
        <given-names>太郎</given-names>
      </string-name>,
      <string-name>
        <surname>鈴木</surname>
        <given-names>一郎</given-names>
      </string-name>.
      <article-title>J-STAGE論文のXML化について</article-title>.
      <source>電子情報通信学会論文誌</source>.
      <year>2023</year>,
      <volume>Vol.106</volume>,
      <issue>No.1</issue>,
      <fpage>p.10</fpage>-<lpage>15</lpage>.
      <pub-id pub-id-type="doi">10.1587/example.10.1</pub-id>
    </mixed-citation>
  </ref>
</ref-list>
```
