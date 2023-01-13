# Sample App
AWSのインフラ構築を体現的に学ぶため、今回のサンプルアプリを使用した。
# 構成図
https://drive.google.com/file/d/1fN6s-CwyQPjfX2jAyAHE3UY-JCPCyti4/view?usp=share_link
# 使用したサービス
・VPC  
・インターネットゲートウェイ  
・NATゲートウェイ  
・ルートテーブル  
・セキュリティグループ  
・IAM  
・EC2  
・Elastic IP  
・Application Load Balancer  
・RDS（MySQL）  
・データベースサーバー  
・パラメータグループ  
・オプショングループ  
・サブネットグループ  
・S3  
・Route 53  
・AWS Certificate Manager  
・Amazon SES  
・ElastiCache  
# パラメータシート
https://drive.google.com/file/d/1LpLw9yA_XqJp6kpW3CLXQ_zSUjIjUWhh/view?usp=share_link
# 今回の学習における所感
○苦労した点  
・SSH接続  
 　configファイルへの書き込みに記入ミスは無かった。調べた結果、configファイルに読み書き権限を付与していないことが原因だと分かったため権限を付与した。その後、SSH接続は成功し、SSH多段接続もすることができた。  
・S3とEC2サーバーの接続  
　エラー文を調べた結果、エンドポイント、ルートテーブル、セキュリティグループのどれかに設定ミスがあることが分かった。一つずつ確認をしたところ、エンドポイントに設定ミスがあったため、設定をやり直した。その結果、S3とEC２サーバーを接続することに成功した。  
○良かった点  
・エラー文や理解できないところを調べながら解決していくことで、理解を深めることができた。  
・代表的なAWSサービスを使うことで、具体的な設定方法や使い方を学ぶことができた。  
・エラーを乗り越えていく度に達成感を味わえ、インフラエンジニアに対する憧れや魅力が増した。  


