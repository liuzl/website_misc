---
title: "Machine Translation"
date: 2022-10-12T12:55:12+08:00
draft: false
---

## Machine Translation


{{< form action="http://localhost:8300/translate">}}
  {{< mult-input id="source" type="select" label="Source language" required="true" >}}
    {{< form-option type="select" label="English" value="en" >}}
    {{< form-option type="select" label="Chinese" value="zh" >}}
  {{< /mult-input >}}
  {{< mult-input id="target" type="select" label="Target language" required="true" >}}
    {{< form-option type="select" label="English" value="en" >}}
    {{< form-option type="select" label="Chinese" value="zh" >}}
  {{< /mult-input >}}
  {{< form-input id="text" type="textarea" placeholder="Make the best advanced usage of modern artificial intelligence technologies to better people's lives." label="Text to translate" required="true" >}}
{{< /form >}}
