# Recommend

Procurement Intelligence for Technology. AI-powered tech recommendations.

## Features

- **Product Recommendations** - Find best tech for your needs
- **Comparison** - Compare products side-by-side
- **Reviews Analysis** - Aggregate and analyze reviews
- **Pricing Insights** - Track and predict prices

## API

```
GET /api/v1/recommend?use_case=...&budget=...
POST /api/v1/recommend/compare
```

## Quick Start

```bash
curl "https://api.openautonomyx.com/api/v1/recommend?use_case=development&budget=500"
```

## Response

```json
{
  "recommendations": [
    { "product": "VS Code", "match_score": 0.95, "price": 0 },
    { "product": "JetBrains", "match_score": 0.89, "price": 149 }
  ]
}
```

## Categories

- **Development** - IDEs, editors, tools
- **Infrastructure** - Cloud, hosting, databases
- **Security** - Auth, scanning, compliance
- **Productivity** - Collaboration, project management

---

**Repository:** [openautonomyx/recommend](https://github.com/openautonomyx/recommend)