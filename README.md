# 🍺 Liquor Shop AI

An AI-powered email automation system built using **n8n**, **Groq AI**, **Gmail API**, and **Excel**.

This workflow automatically understands customer queries written in natural language, searches the inventory, generates professional emails using AI, and sends personalized responses to customers.

---

## Features

- Read customer queries from Excel
- Understand natural language using AI
- Extract filters like:
  - Category
  - Brand
  - Price
  - Bottle Size
  - Premium / Non-premium
  - In-stock items
- Reusable Inventory Service (Child Workflow)
- AI-generated professional emails
- Gmail integration
- Modular n8n architecture

---

## Workflow

Customer Query Excel
↓
Extract Customer Query
↓
AI Filter Extraction
↓
Inventory Service (Child Workflow)
↓
Filter Inventory
↓
AI Email Generation
↓
Send Email using Gmail

---

## Tech Stack

- n8n
- Groq LLM
- Gmail API
- JavaScript
- Excel (.xlsx)

---

## Repository Structure

```
Liquor-Shop-AI/
│
├── Workflows/
│   ├── Liquor-Shop-AI-v1.json
│   └── Inventory-Service-v1.json
│
├── SampleData/
│   ├── CustomerQuery.xlsx
│   └── Inventory.xlsx
│
├── Images/
│
├── Docs/
│
└── README.md
```

---

## Example Customer Queries

- Show me whisky below ₹3000
- Show me all Premium Beers
- Show me all 750ml Whiskies

---

## Example Email

Subject:

```
Whiskey Options Below ₹3000
```

Body:

```
Dear Customer,

Thank you for your enquiry.

We found the following matching products:

• Royal Stag
• Black Dog

Please let us know if you would like to place an order.

Regards,
ABC Liquor Shop
```

---

## Future Enhancements

- WhatsApp integration
- Voice assistant
- Customer purchase history
- Recommendation engine
- Inventory database
- Web dashboard
- Multi-store support

---

## Author

**Mayukh Chakrabarty**

Built with ❤️ using n8n and Groq AI.
