# sbunkov.ru — сайт-визитка Сергея Бунькова

Персональный сайт на русском языке.

## Стек

- Next.js 14, TypeScript, Tailwind CSS
- Статический экспорт → GitHub Pages

## Локальная разработка

```bash
npm install
npm run dev
```

## Деплой

- Репозиторий: [marfa77/sbunkov](https://github.com/marfa77/sbunkov)
- Домен: **https://sbunkov.ru**
- GitHub Actions: `.github/workflows/deploy.yml`

## DNS для sbunkov.ru

У регистратора домена добавьте A-записи для корня `@`:

```text
@  A  185.199.108.153
@  A  185.199.109.153
@  A  185.199.110.153
@  A  185.199.111.153
```

Опционально IPv6:

```text
@  AAAA  2606:50c0:8000::153
@  AAAA  2606:50c0:8001::153
@  AAAA  2606:50c0:8002::153
@  AAAA  2606:50c0:8003::153
```

Для `www.sbunkov.ru`:

```text
www  CNAME  marfa77.github.io
```

После настройки DNS в GitHub: **Settings → Pages → Custom domain** → `sbunkov.ru`, включить **Enforce HTTPS**.

Распространение DNS — от нескольких минут до 24–48 часов.
