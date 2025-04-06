### Prisma 学習

→[参考サイト](https://zenn.dev/hayato94087/books/e9c2721ff22ac7)

### 環境構築

```
pnpm install
```

ローカルデータベースを開始

```
npx supabase start
```

ローカルデータベースを停止

```
npx supabase stop
```

ローカルデータベースをリセット

```
npx supabase db reset
```

Prisma のスキーマのフォーマット

```
pnpm run format:fix
```

Prisma スキーマの検証

```
pnpm run lint
```
