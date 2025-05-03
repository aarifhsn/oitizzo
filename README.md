
## 📌 Installation & Setup

### **1 Clone the Repository**

```bash
git clone https://github.com/aarifhsn/oitizzo.git
cd oitizzo
```

### **2 Install Dependencies**

```bash
composer install
```

### **3 Set Up the Database**

Create a `.env` file and update the database credentials:

```bash
cp .env.example .env
```

Then, run:

```bash
php artisan migrate --seed
```

(Seeding will create a default admin user.)