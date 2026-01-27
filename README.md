# NotlarSende (NotesOnYou)

[English](#english) | [Türkçe](#türkçe)

---

<a name="english"></a>
## 🇬🇧 English

**NotlarSende** is a web-based platform designed for sharing and selling educational notes, documents, and other digital materials. Users can upload their own content, browse available products, add them to their cart, and simulate a purchasing process.

### Features

*   **User Management:** Registration, Login, and Profile management.
*   **Product Management:** Users can upload files (PDF, DOCX, PPTX) and publish them with details (Title, Price, Description, etc.).
*   **Shopping Cart:** Add products to cart, view total price, and simulate purchase.
*   **Storefront:** Browse all published products.
*   **Support System:** Users can submit support tickets regarding products.
*   **Downloads:** Secure download links for purchased items.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/username/NotlarSende.git
    cd NotlarSende
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    # Windows:
    venv\Scripts\activate
    # Mac/Linux:
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install flask
    ```

4.  **Run the application:**
    ```bash
    python app.py
    ```

5.  Open your browser and navigate to `http://localhost:5000`.

### Technologies Used

*   **Backend:** Python, Flask
*   **Frontend:** HTML, CSS (Bootstrap-like structure assumed), JavaScript
*   **Database:** JSON-based local storage (No external database required for demo).

---

<a name="türkçe"></a>
## 🇹🇷 Türkçe

**NotlarSende**, eğitim notları, belgeler ve diğer dijital materyallerin paylaşılması ve satılması için tasarlanmış web tabanlı bir platformdur. Kullanıcılar kendi içeriklerini yükleyebilir, mevcut ürünlere göz atabilir, sepete ekleyebilir ve satın alma sürecini simüle edebilirler.

### Özellikler

*   **Kullanıcı Yönetimi:** Kayıt Ol, Giriş Yap ve Profil yönetimi.
*   **Ürün Yönetimi:** Kullanıcılar dosya yükleyebilir (PDF, DOCX, PPTX) ve bunları detaylarla (Başlık, Fiyat, Açıklama vb.) yayınlayabilir.
*   **Alışveriş Sepeti:** Ürünleri sepete ekleme, toplam tutarı görme ve satın alma simülasyonu.
*   **Mağaza:** Yayınlanan tüm ürünleri görüntüleme.
*   **Destek Sistemi:** Kullanıcılar ürünlerle ilgili destek talebi oluşturabilir.
*   **İndirmeler:** Satın alınan ürünler için güvenli indirme bağlantıları.

### Kurulum

1.  **Projeyi klonlayın:**
    ```bash
    git clone https://github.com/kullaniciadi/NotlarSende.git
    cd NotlarSende
    ```

2.  **Sanal ortam oluşturun ve etkinleştirin:**
    ```bash
    python -m venv venv
    # Windows:
    venv\Scripts\activate
    # Mac/Linux:
    source venv/bin/activate
    ```

3.  **Gerekli kütüphaneleri yükleyin:**
    ```bash
    pip install flask
    ```

4.  **Uygulamayı çalıştırın:**
    ```bash
    python app.py
    ```

5.  Tarayıcınızı açın ve `http://localhost:5000` adresine gidin.

### Kullanılan Teknolojiler

*   **Backend:** Python, Flask
*   **Frontend:** HTML, CSS, JavaScript
*   **Veritabanı:** JSON tabanlı yerel depolama (Demo için harici veritabanı gerektirmez).

---

### ⚠️ Security Note / Güvenlik Notu

This project is a demonstration/prototype.
*   **Passwords are stored in plain text.** (Şifreler düz metin olarak saklanmaktadır.)
*   **Secret keys are hardcoded.** (Gizli anahtarlar kod içinde tanımlıdır.)
*   **Not suitable for production without security hardening.** (Güvenlik iyileştirmeleri yapılmadan canlı ortamda kullanıma uygun değildir.)
