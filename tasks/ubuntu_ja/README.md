# Ubuntu 日本語 タスク

## ノードのメタデータ

- 'timezone' (オプション) - タイムゾーンを変更する
  - デフォルト値: Asia/Tokyo
- 'admin_user' (オプション)　- 管理者ユーザのユーザ名
- 'admin_pass' (オプション)  - 管理者ユーザのパスワード
- 'hostname' (オプション) - ホスト名
- 'enable_serialconsole' (オプション) - シリアルコンソールを利用するか(true/false) [9600bps固定]
  - デフォルト値: false
- 'repo_host' (オプション)　レポジトリのホスト名
- 'repo_path' (オプション)  レポジトリのパス

repo_hostとrepo_pathは同時に設定した時のみ有効です。どちらか一方しか設定がない場合は、無効として判断します。
