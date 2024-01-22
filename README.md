# AzureOpenAI essential notebooks
Azure OpenAIを使ったさまざまなシナリオの基本を学ぶためのプリミティブなJupyter Notebookサンプル集です。
Pull Requestウェルカムです。いきなりPRを出していただいてもいいですし、Issueから立てていただくのも歓迎です。
こんなことはどうだろうか？と迷う方は[@07JP27](https://twitter.com/07JP27)までお気軽にご連絡ください。

 - [Feature](./Feature)：Azure OpenAIの機能を説明するサンプル集
 - [PromptEngineering](./PromptEngineering)：プロンプトエンジニアリングの各手法を説明するサンプル集
 - [RAG](./RAG)：LLMに対して追加の知識を獲得させる手法であるRAG:Retrieval Augmented Generation(検索拡張生成)のためのサンプル集


 ## 実行方法
1. .env-sampleファイルを同じ階層にコピーします。
1. コピーしたファイルを.envにリネームします。
1. .env内の各環境変数をご自身の情報に書き換えてください。
1. Notebookを実行します。

※スポットで実行する場合は各Notebookで環境変数を読み込んでいるコード（os.environ['xxx']の部分）を値で直接上書いても動作します。

