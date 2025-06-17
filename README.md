# llm-rag-agents-demo

Basics Python project for LLM, RAG, and Agents

## Prerequisites

```yaml
python: 3.x
```

For details, please refer [here](https://qiita.com/minorun365/items/33d063bc62bbca1824a9)

## Getting Started

### LLM API

- Amazon Bedrock の[Converse API](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/conversation-inference.html)を使います。

- [ConverseSetream API](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/bedrock-runtime_example_bedrock-runtime_ConverseStream_AnthropicClaude_section.html)を使います。

- 簡単なフロントエンド: Python ライブラリ[「Streamlit」](https://docs.streamlit.io/)を使います。

### RAG (Retrieval-Augmented Generation)

- Meta 社のベクトルインデックス作成 OSS[「Faiss」](https://github.com/facebookresearch/faiss)を使います。

- LLM アプリでよく使う処理を簡単に書ける[「LangChain」](https://python.langchain.com/docs/introduction/)を使います。

- クラウド上に RAG アプリを構築: AWS のマネージドサービス[「Bedrock ナレッジベース」](https://qiita.com/minorun365/items/24dfb0ea3afde6ed0a56)を使います。

### AI Agent

- Converse API の[Tool Use 機能](https://docs.aws.amazon.com/ja_jp/bedrock/latest/userguide/tool-use-inference-call.html)を使います。

- AI エージェントを簡単に書ける AWS 製の OSS[「Strands Agents SDK」](https://strandsagents.com/latest/)を使います。

- 簡単なフロントエンド: Python ライブラリ[「Streamlit」](https://docs.streamlit.io/)を使います。

- クラウド上に AI エージェントを構築: AWS のマネージドサービス[「Bedrock エージェント」](https://qiita.com/minorun365/items/edc8bc7808840b308b5c)を使います。

---

&copy; 2025 All rights reserved.
