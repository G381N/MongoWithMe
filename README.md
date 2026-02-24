<div align="center">

# 🍃 LearnMongoWithMe

### _A hands-on journey through MongoDB — learn it as I learn it._

[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-In_Progress-blue?style=for-the-badge)]()

</div>

---

## 📌 What Is This?

Welcome to **LearnMongoWithMe** — a living, breathing repository where I document everything I learn about MongoDB, step by step. This isn't a polished textbook; it's a real-time learning journal. Every concept, every command, every "aha!" moment is captured here so that **you can learn alongside me**.

Whether you're a complete beginner or brushing up on your NoSQL skills, you'll find:

- ✅ Clear explanations written in plain English
- ✅ Copy-paste ready commands
- ✅ Real output snippets so you know what to expect
- ✅ Progressive topics — each section builds on the last

> **💡 Tip:** Start from the top and work your way down. Each document links to the next, so you can follow the entire journey in order.

---

## ⚡ Quick Access

Jump straight to what you need:

| # | Topic | Description | Link |
|:-:|:------|:------------|:----:|
| 1 | **Getting Started** | Connecting to MongoDB & navigating databases | [Go →](1.GettingStarted.md) |
| 2 | **Inserting Documents** | Creating collections & your first data | [Go →](2.InsertingDocuments.md) |
| 3 | **Reading Documents** | Retrieving data with `find()` & `findOne()` | [Go →](3.ReadingDocuments.md) |
| 4 | **Updating Documents** | Modifying data with `updateOne()` & `updateMany()` | [Go →](4.UpdatingDocuments.md) |
| 5 | **Querying Documents** | Filtering, counting & nested queries | [Go →](5.QueryingDocuments.md) |
| 6 | **CRUD Overview** | The four fundamental operations at a glance | [Go →](6.CRUDOverview.md) |
| 7 | **CRUD — Read** | Deep dive into read operations | [Go →](7.CRUDRead.md) |
| 8 | **CRUD — Create** | Deep dive into create operations | [Go →](8.CRUDCreate.md) |

---

## 📚 Full Index

Below is the complete table of contents for every topic covered in this repository. New sections will be added as I continue learning!

### 🔰 Getting Started

1. **[Getting Started — Connecting & Navigating](1.GettingStarted.md)**
   - What is `mongosh`?
   - Connecting to MongoDB (local & Atlas)
   - Show databases, switch databases
   - Show collections, check current database

2. **[Inserting Documents — Your First Data](2.InsertingDocuments.md)**
   - Collections vs Documents vs Fields
   - Creating a collection (the easy way)
   - Inserting your first document with `insertOne()`
   - Understanding the output

3. **[Reading Documents — Retrieving Your Data](3.ReadingDocuments.md)**
   - `find()` — retrieve all documents
   - `findOne()` — retrieve a single document
   - When to use `find()` vs `findOne()`

4. **[Updating Documents — Modifying Your Data](4.UpdatingDocuments.md)**
   - The `$set` operator
   - `updateOne()` — update a single document
   - `updateMany()` — update all matching documents
   - Adding nested objects and arrays

5. **[Querying Documents — Searching Your Data](5.QueryingDocuments.md)**
   - Basic filtering by field values
   - Counting results with `.count()`
   - Querying nested documents with dot notation

### 🔄 CRUD Operations

6. **[CRUD Overview](6.CRUDOverview.md)**
   - What is CRUD?
   - Create — `insertOne()`, `insertMany()`
   - Read — `find()`, `findOne()`
   - Update — `updateOne()`, `updateMany()`, `replaceOne()`
   - Delete — `deleteOne()`, `deleteMany()`

7. **[CRUD — Read (Deep Dive)](7.CRUDRead.md)**
   - Comparison operators (`$gt`, `$gte`, `$lt`, `$lte`, `$eq`, `$ne`)
   - Logical operators (`$or`, `$and`)
   - Projection — selecting specific fields
   - Sorting and limiting results
   - Method chaining
   - Iterating with `forEach`

8. **[CRUD — Create (Deep Dive)](8.CRUDCreate.md)**
   - `insertOne()` — inserting a single document
   - `insertMany()` — inserting multiple documents
   - The `_id` field and ObjectId anatomy
   - Ordered vs unordered inserts
   - Write concerns
   - Common errors and fixes

---

## 🗺️ Roadmap

Here's what's coming next as I continue the journey:

- [ ] **CRUD — Update (Deep Dive)** — `$set`, `$unset`, `$inc`, `$push`, `$pull`, and more
- [ ] **CRUD — Delete (Deep Dive)** — Safe deletion patterns
- [ ] **Indexing** — Creating and managing indexes for performance
- [ ] **Aggregation Framework** — Pipelines, `$match`, `$group`, `$project`
- [ ] **Schema Design** — Embedding vs referencing, best practices
- [ ] **MongoDB with Node.js** — Using the native driver and Mongoose

---

## 🧭 How to Navigate

Every markdown file in this repo follows a consistent structure:

1. **Title & Introduction** — What the topic is about  
2. **Table of Contents** — Quick jump links  
3. **Concepts** — Theory and explanation  
4. **Commands** — Copy-paste ready code blocks  
5. **Output** — What you should see in your terminal  
6. **Navigation** — Links to the previous and next sections  

> Each file has **⬅️ Previous** and **➡️ Next** links at the bottom so you can read through the entire repo like a book.

---

## 🛠️ Prerequisites

Before you start, make sure you have:

- [MongoDB Community Server](https://www.mongodb.com/try/download/community) installed
- Access to `mongosh` (the MongoDB Shell)
- A terminal / command prompt

```bash
# Verify your installation
mongosh --version
```

---

## 🤝 Contributing

Found a typo? Have a better explanation? Feel free to open a PR or issue. This is a learning repo, and learning is better together!

---

## 📄 License

This project is licensed under the MIT License — feel free to use, share, and learn from it.

---

<div align="center">

**Made with 💚 by [Gebin](https://github.com/gebin)**

_Happy Learning! 🍃_

</div>
