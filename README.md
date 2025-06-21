# Pokemon TCG 数据同步

## 2025-06-21T14:14:58Z

## 数据统计
- **版本号**: v2
- **总卡片数量**: 19155 张
- **卡组数量**: 166 个
- **数据来源**: [Pokemon TCG API](https://pokemontcg.io/)

## 数据结构
```json
{
  "totalCount": 数字,
  "version": 数字,
  "data": [
    {
      "set": {
        "id": "set_id",
        "name": "set_name"
      },
      "cards": [...]
    }
  ]
}
```

## 自动更新
此数据每2小时自动更新一次，确保数据的时效性。

---
*数据由 GitHub Actions 自动维护*
