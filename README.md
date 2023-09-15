# README

## 開発言語
- Ruby 3.0.1
- Ruby on Rails 6.1.7

## テーブル
### user
| カラム | データ型 |
| ---- | ---- |
| name | string |
| email | string |
| password_digest | string |

### task
| カラム | データ型 |
| ---- | ---- |
| title | string |
| content | text |
| user_id | bigint |