# ai-hub-deck

ai-hub-deck は、作成者本人が自分の予定と ToDo を 1 画面で確認するための、個人用ダッシュボードです。一般向けに配布・提供しているアプリではありません。

## このアプリが行うこと

- 作成者本人の Google アカウントの Google ToDo（Google Tasks）を、読み取り専用で取得します。
- 取得した ToDo を、作成者が管理する非公開ネットワーク内のダッシュボード画面に表示します。

## 利用する Google の権限

- `https://www.googleapis.com/auth/tasks.readonly`（ToDo の閲覧のみ）

ToDo の作成・変更・削除は行いません。

## 利用者

作成者本人のみです。第三者の Google アカウントでの利用は想定していません。

## プライバシー ポリシー

[PRIVACY.md](./PRIVACY.md) をご覧ください。

---

# ai-hub-deck (English)

ai-hub-deck is a personal dashboard used only by its author to view the author's own schedule and to-do items on one screen. It is not distributed or offered to the public.

- It reads the author's own Google Tasks in read-only mode (`tasks.readonly`).
- It displays those tasks on a dashboard inside the author's private network.
- It does not create, change or delete tasks.

Privacy policy: [PRIVACY.md](./PRIVACY.md)
