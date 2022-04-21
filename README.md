# 2021 年前端/UI 從業人員現況問卷調查 API

> 此問卷是2021 年前端/UI 從業人員現況問卷調查結果生成出來的 API，主要有兩隻 JSON 可供使用。

## API 介紹

- ~~每十二小時自動更新。~~
- 撈取 Google 表單所建立的 Google Sheet。
- 採 GitHub Action 自動部署。

## frontend_data.json

> 前端從業人員資料

API Url：[https://raw.githubusercontent.com/hexschool/2021-ui-frontend-job/master/frontend_data.json](https://raw.githubusercontent.com/hexschool/2021-ui-frontend-job/master/frontend_data.json)

### 前端欄位說明

```json
{
  "job": "", // 職稱
  "gender": "", // 性別
  "age": "", // 年齡
  "education": "", // 學歷
  "major": "", // 科系
  // 第一份工作
  "first_job": {
    "tenure": "", // 第一份年資
    "leave": "", // 第一份工作離職原因
    "position": "", // 第一份工作被要求非前端工程師的技能
    "skill": "", // 第一份工作上公司所導入的技能
    "render": ""  // 接觸到哪一種開發模式
  },
  // 工作相關
  "works": {
    "window": "", // 主要是哪些窗口有溝通障礙
    "market": "" // 自評工作能力範圍
  },
  // 目前公司
  "company": {
    "industry": "", // 產業類型
    "score": "", // 產業滿意度
    "work": "", // 工作型態
    "area": "", // 公司位置
    "scale": "", // 公司規模人數
    "people": "", // 相同職位人數 
    "job_tenure": "", // 工作年資
    "salary": "", // 年薪範圍
    "salary_score": "", // 薪水滿意度
    "industry_message": "" // 產業簽到區
  }
}
```

## ui_data.json

> UI 從業人員資料

API Url：[https://raw.githubusercontent.com/hexschool/2021-ui-frontend-job/master/ui_data.json](https://raw.githubusercontent.com/hexschool/2021-ui-frontend-job/master/ui_data.json)

### UI 欄位說明

```json
{
  "job": "", // 職稱
  "name": "", // 姓名
  "gender": "", // 性別
  "age": "", // 年齡
  "education": "", // 學歷
  "major": "", // 科系
  // 第一份工作
  "first_job": {
    "tenure": "", // 第一份年資
    "leave": "", // 第一份離職原因
    "content": "", // 第一份工作內容
    "skill": "", // 你掌握哪些開發技能
    "software": "" // 公司主要使用哪些繪圖軟體
  },
  // 工作相關
  "works": {
    "window": "", // 主要是哪些窗口有溝通障礙
  },
  // 目前公司
  "company": {
    "industry": "", // 產業類型
    "score": "", // 產業滿意度
    "work": "", // 工作型態
    "area": "", // 公司位置
    "scale": "", // 公司規模人數
    "people": "", // 相同職位人數 
    "job_tenure": "", // 工作年資
    "salary": "", // 年薪範圍
    "salary_score": "", // 薪水滿意度
    "industry_message": "" // 產業簽到區
  }
}
```

## 常見問題

Q: 串接到一半突然接不上了！
A: 通常這種狀況在於太多人請求導致，所以大約等候一小時不等就可以恢復正常。

若有其他相關問題可開啟 Issues 告知。
