基于Apache tika和Apache lucene的全文检索系统

搜索结果返回的是org.apache.lucene.document的List列表\n
搜索结果标题的获取：documentList.get(i).get("title")
搜索结果内容的获取：documentList.get(i).get("contents")
