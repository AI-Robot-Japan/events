# Example Event / イベント例

```json
{
  "id": "example-ai-event-2024",
  "title": {
    "ja": "AI技術カンファレンス 2024",
    "en": "AI Technology Conference 2024"
  },
  "description": {
    "ja": "最新のAI技術とその応用について学べるカンファレンスです。",
    "en": "A conference to learn about the latest AI technologies and their applications."
  },
  "date": {
    "start": "2024-06-15T09:00:00+09:00",
    "end": "2024-06-15T18:00:00+09:00"
  },
  "location": {
    "venue": {
      "ja": "東京国際フォーラム",
      "en": "Tokyo International Forum"
    },
    "address": "〒100-0005 東京都千代田区丸の内3-5-1",
    "city": "Tokyo",
    "country": "Japan"
  },
  "organizer": {
    "name": "AI Robot Japan",
    "contact": "info@ai-robot-japan.example.com",
    "website": "https://ai-robot-japan.example.com"
  },
  "categories": [
    "AI",
    "Machine Learning",
    "Conference"
  ],
  "language": ["ja", "en"],
  "registration": {
    "required": true,
    "url": "https://example.com/register",
    "deadline": "2024-06-01T23:59:59+09:00",
    "fee": {
      "amount": 5000,
      "currency": "JPY"
    }
  },
  "capacity": 500,
  "status": "upcoming"
}
```

## Field Descriptions / フィールドの説明

- **id**: Unique identifier for the event / イベントの一意識別子
- **title**: Event title in multiple languages / 複数言語でのイベントタイトル
- **description**: Detailed description / 詳細な説明
- **date**: Event start and end times / イベントの開始時刻と終了時刻
- **location**: Event location details / イベント会場の詳細
- **organizer**: Event organizer information / イベント主催者情報
- **categories**: Event categories/tags / イベントのカテゴリ/タグ
- **language**: Supported languages / サポートされる言語
- **registration**: Registration information / 登録情報
- **capacity**: Maximum number of attendees / 最大参加者数
- **status**: Event status (upcoming, ongoing, completed, cancelled) / イベントステータス

## Usage / 使用方法

Copy this template and modify it to create new events.
このテンプレートをコピーして、新しいイベントを作成するために変更してください。

```bash
cp examples/event-template.json data/events/your-event.json
# Edit the file with your event details
```
