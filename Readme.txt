# 🚀 Alpha — Investment Blog Platform

**Alpha** is a modern investment-focused blog built to deliver high-quality content across multiple financial domains including **Crypto, Stocks, ETFs, Gold, Trading, AI, and Startups**.

The platform is designed to simulate a real-world financial media site with structured content, categories, tags, and dynamic engagement metrics.


![Dashboard](README-assets/dashboard.png)


---

## 📌 Features

* 🧩 **Categories System**

  * Organize content into major topics (Crypto, Stocks, ETFs, etc.)

* 🏷️ **Tags System**

  * Fine-grained filtering (Bitcoin, Ethereum, DeFi, AI, etc.)

* 📝 **Posts Management**

  * Rich content (HTML supported)
  * SEO-friendly slugs
  * Featured images

* 🔗 **Many-to-Many Relationships**

  * Posts ↔ Categories
  * Posts ↔ Tags

* 📊 **Dynamic Views Counter**

  * Simulated engagement with randomized views

* ⚡ **Scalable Structure**

  * Built for expansion (Admin panel, trending system, recommendations)

![Home Page](README-assets/home.png)


---

## 🗄️ Database Structure

### Main Tables:

* `posts`
* `categories`
* `tags`

### Pivot Tables:

* `category_post`
* `post_tag`

---

## 🧠 Content Strategy

Alpha focuses on a mix of:

* 🟡 **Safe Assets** → Gold, ETFs
* 🟣 **High Growth** → Crypto, AI
* 🟢 **Stable Investing** → Stocks, Dividends
* 🔴 **High Risk** → Meme Coins, Startups
* 🧠 **Education** → Trading, Guides, Risk Management

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/AhmadAlabrash/alpha-blog.git
```

### 2. Setup Database

* Create a MySQL database
* Import SQL structure and data

### 3. Configure Environment

Update `.env` file:

```env
DB_DATABASE=your_database
DB_USERNAME=root
DB_PASSWORD=
```

---

## 📥 Sample Data

The project includes:

* ✅ Categories (Crypto, Stocks, ETFs, etc.)
* ✅ Tags (Bitcoin, Ethereum, DeFi, etc.)
* ✅ 20+ Professional Blog Posts
* ✅ Relationships (Posts ↔ Tags ↔ Categories)

---

## 📈 Future Improvements

* 🔥 Trending posts system (based on views)
* 🧠 Recommended articles engine
* 🏷️ Tag pages (`/tag/bitcoin`)
* 📊 Category landing pages
* 🧑‍💻 Admin dashboard (CRUD)
* 🌐 SEO optimization

---

## 💡 Vision

Alpha is not just a blog — it is designed to become a **financial content platform** that blends:

* Data-driven insights
* High-quality writing
* Real-world investment narratives

---

## ⚠️ Notes

* Ensure pivot tables use **UNIQUE constraints** to avoid duplicate relationships.
* Use `INSERT IGNORE` for bulk linking queries.
* Always verify IDs before running bulk inserts.

---

## 👨‍💻 Author

Built as a scalable investment content system focused on modern financial markets.

---

## 📜 License

This project is open for learning and development purposes.
