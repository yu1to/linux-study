# Linux基礎環境構築（WSL2 + Ubuntu）

## ■ 目的
Linux基礎スキル習得およびサーバ構造理解を目的とする。
クラウドエンジニアに必要なLinux操作を実践形式で学習。

---

## ■ 環境

- Windows 11
- WSL2
- Ubuntu
- Nginx
- PostgreSQL

---

## ■ 実施手順

```powershell
wsl --install
wsl -l -v
```
---

## ■ 学んだこと

- Linuxはファイル操作がすべての基礎である
- root権限の重要性を理解した
- サービスはsystemctlで管理されている
- WebサーバとDBはポートで通信している

---

## ■ 詰まった点

- WSLのバージョン確認方法
- nginxが起動しない原因調査

---

## ■ 今後の改善

- シェルスクリプトで自動化
- SSH鍵認証設定
- Azure VM上で再構築
