

# 🍕 Pizza Sales Data Analysis (PostgreSQL + Power BI)

Bu layihə pizza satış məlumatlarını təhlil etmək və satış performansını qiymətləndirmək məqsədi ilə hazırlanıb.  
Dataset, müxtəlif pizza növlərinin satışlarını, qiymətlərini, sifariş tarixlərini və kateqoriyalarını əhatə edir.

---

## 📊 Layihənin məqsədi
Layihənin əsas məqsədi:
- Satış məlumatlarını təmizləmək və **PostgreSQL** bazasına yükləmək
- SQL sorğuları vasitəsilə satış performansını analiz etmək
- **Power BI** vasitəsilə vizuallaşdırma və dashboard hazırlamaq

---

## 🧩 Dataset haqqında
| Sütun adı | Açıqlama |
|------------|-----------|
| `pizza_id` | Unikal pizza ID |
| `order_id` | Sifariş nömrəsi |
| `pizza_name_id` | Pizza-nın kod adı |
| `quantity` | Sifariş edilən miqdar |
| `order_date` | Sifariş tarixi |
| `order_time` | Sifariş vaxtı |
| `unit_price` | Bir pizza-nın qiyməti |
| `total_price` | Ümumi qiymət (miqdar × qiymət) |
| `pizza_size` | Pizza ölçüsü (S, M, L, XL, XXL) |
| `pizza_category` | Kateqoriya (Classic, Supreme, Veggie və s.) |
| `pizza_ingredients` | Pizza tərkibi |
| `pizza_name` | Pizza-nın tam adı |


