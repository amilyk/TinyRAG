RAG步骤
1. 文档加载和切分模块
2. 文本向量化emb
3. 建立向量数据库和检索
4. 检索结果作为上下文放到大模型里回答用户问题

QA
1. 发现多个文件用于RAG效果不如一个文件, 相似度计算要返回多个作为参考.emb相似度return对齐改对了.
2. 不用langchain处理文件读入和处理，效果很差。

