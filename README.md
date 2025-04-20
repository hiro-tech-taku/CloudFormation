# 同テンプレート内でのIDの参照→Ref関数を使用（vpcの参照）
VpcId: !Ref VPC

# 別テンプレートからIDの参照（クロススタック参照）
Outputsセクション（参照元）とImportValue関数（参照先）を使用

下記の記事を参考にメモしていく。
https://dev.classmethod.jp/articles/cfn-cross-stack-reference/

# 他にCloudFormationで気になることがあれば追記予定
