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
・Route ５３
・AWS Certificate Manager
・Amazon SES
・ElastiCache
# パラメータシート
https://drive.google.com/file/d/1LpLw9yA_XqJp6kpW3CLXQ_zSUjIjUWhh/view?usp=share_link
#　　今回の学習における所感
・DBへの接続や、S3へのアップロードが上手くいかず難航した。エラー文を調べた結果、エンドポイントの設定に不備があることが分かり、修正することで接続することができた。
・初めてコマンドを使用して、サーバーへの接続、インストール等を行った。CUIベースでの作業に馴染みが無かったが、今回の構築を通して、コマンド操作の重要性を理解することができた。AWS構築のことばかりではなく、Linuxについても学習していきたい。
