# CliendlySolutions Strategix Suite

**CliendlySolutions Strategix Suite**, modern bir ERP & Yönetim paneli çözümüdür.  
Django üzerine inşa edilmiştir ve **Unfold Admin** ile modern bir arayüz sunar.  
Projede kullanıcı, grup, raporlama ve dashboard yönetimi gibi modüller bulunmaktadır.

---

## 🚀 Özellikler

- 🔐 Kullanıcı ve grup yönetimi  
- 📊 Dashboard & Chart görselleştirmeleri  
- 🧩 Modüler yapı (müşteri, sipariş, kullanıcı işlemleri)  
- 🎨 Modern ve özelleştirilebilir admin panel (Unfold)  
- 🌍 Türkçe dil desteği  

---

## ⚙️ Kurulum

Projeyi klonlayın ve kurulumu gerçekleştirin:

```bash
git clone https://github.com/OFKasarcioglu/CliendlySolutionsStrategixSuite.git
cd CliendlySolutionsStrategixSuite
python -m venv venv
source venv/bin/activate   # MacOS/Linux için
# venv\Scripts\activate    # Windows için

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
