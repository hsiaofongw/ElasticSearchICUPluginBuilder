# ElasticSearch 自定义 Image 构建仓库

按照 ES 官网文档：

1. [k8s-custom-images](https://www.elastic.co/guide/en/cloud-on-k8s/current/k8s-custom-images.html)
2. [analysis-icu](https://www.elastic.co/guide/en/elasticsearch/plugins/current/analysis-icu.html)

编写的用于构建包含了 `analysis-icu` 插件的自定义 ElasticSearch 容器镜像。

`analysis-icu` 插件提供了更好用的，适用于 CJK 语言的，Analyzer（分析器，或者分词器）`icu_analyzer`.
